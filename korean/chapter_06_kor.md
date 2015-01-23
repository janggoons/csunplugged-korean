## Activity 6 활동 6
### Battleships—Searching Algorithms 전함 놀이 - 검색 알고리즘
#### Summary 요약
Computers are often required to find information in large collections of data. They need to develop quick and efficient ways of doing this. This activity demonstrates three different search methods: linear searching, binary searching and hashing.
컴퓨터는 수많은 데이터들 속에서 원하는 정보를 찾는 작업을 종종 수행합니다. 그래서, 이러한 검색 작업을 빠르고 효과적으로 수행할 수 있는 방법이 필요합니다. 이번 활동에서는 세 가지 검색 방법(선형 검색, 이진 검색, 해싱)을 따라해 봅시다.


#### Curriculum Links 관련 교과
- Mathematics: Number Level 3 and up. 수학: 숫자 레벨 3 이상
- Exploring numbers: Greater than, less than and equal to 숫자 탐색: >, <, =
- Geometry Level 3 and up. 기하: 레벨 3 이상
- Exploring shape and space: Co-ordinates 형태와 공간 탐색: 좌표

#### Skills 필요 능력
- Logical reasoning 논리적 추론

#### Ages 나이
- 9 years and up 9세 이상

#### Materials 자료
- Each child will need: 학생들은 각각 다음 자료가 필요함:
	- Copy of battleships games 전함 놀이 활동지
	- 1A, 1B for game 1 첫번째 게임을 위한 1A, 1B 활동지
	- 2A, 2B for game 2 두번째 게임을 위한 2A, 2B 활동지
	- 3A, 3B for game 3 세번째 게임을 위한 3A, 3B 활동지
	- You may also need a few copies of the supplementary game sheets, 1A', 1B', 2A', 2B', 3A', 3B'. 추가 게임을 위해 여분의 1A', 1B', 2A', 2B', 3A', 3B' 활동지

### Battleships 전함 놀이
#### Introductory Activity 시작 활동
1. Choose about 15 children to line up at the front of the classroom. Give each child a card with a number on it (in random order). Keep the numbers hidden from the rest of the class. 15명의 학생들을 선택하여 교실 앞쪽에 줄을 세웁니다. 그리고 학생들에게 서로 다른 숫자가 적힌 카드를 무작위로 나눠줍니다. 이때 교실에 앉아 있는 다른 학생들은 숫자를 볼 수 없도록 합니다.
2. Give another child a container with four or five sweets in it. Their job is to find a given number. They can “pay” to look at a particular card. If they find the correct number before using all their sweets, they get to keep the rest. 앉아있는 학생들 중 한명에게4~5개의 사탕이 들어있는 상자를 줍니다. 그 학생의 역할은 지정된 숫자를 찾는 것입니다. 사탕을 가진 학생은 사탕을 "지불"하여 특정 카드를 볼 수 있습니다. 만약 사탕을 모두 사용하기 전에 지정된 숫자를 찾는다면, 그들은 휴식을 취할 수 있습니다.
3. Repeat if you wish to. 원하는 만큼 반복하세요.
4. Now shuffle the cards and give them out again. This time, have the children sort themselves into ascending order. The searching process is repeated. 이제 카드를 다시 섞고, 숫자를 다시 지정해 줍니다. 이번에는 학생들이 작은 숫자에서 큰 숫자로 정렬합니다. 그리고 숫자를 찾는 과정을 반복합니다.

If the numbers are sorted, a sensible strategy is to use just one “payment” to eliminate half the children by having the middle child reveal their card. By repeating this process they should be able to find the number using only three sweets. The increased efficiency will be obvious.
숫자들이 정렬되어 있다면, 합리적인 검색 방법은 순서대로 서 있는 학생들 중 가운데 학생의 숫자를 선택함으로써 단 하나의 사탕 "지불"로 절반의 학생들을 제외할 수 있습니다. 이 과정을 반복하면 단 3개의 사탕으로 숫자를 찾을 수 있습니다.

#### Activity 활동하기
The children can get a feel for how a computer searches by playing the battleship game. As they play the game, get them to think about the strategies they are using to locate the ships.
전함 놀이를 하면서 학생들은 컴퓨터가 어떻게 검색하는지를 익힐 수 있습니다. 놀이를 하면서, 학생들은 전함의 위치를 찾아내는 전략을 생각할 수 있습니다.


### Battleships—A Linear Searching Game 전함 놀이 - 선형 검색
#### Read the following instructions to the children 학생들을 위해 다음 설명 읽기
1. Organise yourselves into pairs. One of you has sheet 1A, the other sheet 1B. Don’t show your sheet to your partner! 여러분들 스스로 2명씩 짝을 만드세요. 한 명은 1A 활동지, 다른 한 명은 1B 활동지를 받습니다. 자기가 갖고 있는 활동지를 짝에게 보여주지 마세요!
2. Both of you circle one battleship on the top line of your game sheet and tell your partner its number. 각자 활동지의 맨 윗 줄에 있는 전함 중 하나에 동그라미 표시를 하고, 상대방에게 그 전함의 숫자를 알려줍니다.
3. Now take turns to guess where your partner’s ship is. (You say the letter name of a ship and your partner tells you the number of the ship at that letter.) 이제 서로 번갈아 가면서 상대방의 전함을 추측해 보세요. (한 명이 전함의 이름을 말하면, 상대방은 그 이름에 해당하는 전함 번호를 알려줍니다.)
4. How many shots does it take to locate your partner’s ship? This is your score for the game. 몇 번 만에 상대방의 전함을 찾았나요? 그 횟수가 이 놀이에서 여러분이 획득한 점수입니다.

(Sheets 1A' and 1B' are extras provided for children who would like to play more games or who “inadvertently” see their partner’s sheet. Sheets 2A', 2B' and 3A', 3B' are for the later games.)
(1A' 과 1B' 은 놀이를 더 해보고 싶거나, "우연히" 상대방의 종이를 본 학생들을 위한 추가 활동지 입니다. 2A' 과 2B', 3A' 과 3B' 역시 뒤에서 할 게임의 추가 활동지 입니다.)

#### Follow Up Discussion 토론하기
1. What were the scores? 획득한 점수는 몇 점인가요?
2. What would be the minimum and maximum scores possible? (They are 1 and 26 respectively, assuming that the children don’t shoot at the same ship twice. This method is called ‘linear search’, because it involves going through all the positions, one by one.) 획득 가능한 최소 점수와 최대 점수는 몇 점일까요? (학생들이 동일한 전함을 두 번 선택하지 않는다고 가정한다면, 1점에서 26점 입니다. 이런 방법은 모든 위치를 한 번씩 살펴보기 때문에 '선형 검색' 이라고 부릅니다.)

### Battleships—A Binary Searching Game 전함 놀이 - 이진 검색
#### Instructions 설명
The instructions for this version of the game are the same as for the previous game but the numbers on the ships are now in ascending order. Explain this to the children before they start.
이번 활동은 이전 활동과 동일하지만 전함에 기록된 숫자가 오름차순으로 정렬되어 있습니다. 이번 활동을 시작하기 전에 학생들에게 설명해 주세요.

1. Organise yourselves into pairs. One of you has sheet 2A, the other sheet 2B. Don’t show your sheet to your partner! 여러분들 스스로 2명씩 짝을 만드세요. 한 명은 2A 활동지, 다른 한 명은 2B 활동지를 받습니다. 자기가 갖고 있는 활동지를 짝에게 보여주지 마세요!
2. Both of you circle one battleship on the top line of your game sheet and tell your partner its number. 각자 활동지의 맨 윗 줄에 있는 전함 중 하나에 동그라미 표시를 하고, 상대방에게 그 전함의 숫자를 알려줍니다.
3. Now take turns to guess where your partner’s ship is. (You say the letter name of a ship and your partner tells you the number of the ship at that letter.) 이제 서로 번갈아 가면서 상대방의 전함을 추측해 보세요. (한 명이 전함의 이름을 말하면, 상대방은 그 이름에 해당하는 전함 번호를 알려줍니다.)
4. How many shots does it take to locate your partner’s ship? This is your score for the game. 몇 번 만에 상대방의 전함을 찾았나요? 그 횟수가 이 놀이에서 여러분이 획득한 점수입니다.

#### Follow Up Discussion 토론하기
1. What were the scores? 획득한 점수는 몇 점인가요?
2. What strategy did the low scorers use? 낮은 점수를 얻기 위해 어떤 전략을 사용했나요?
3. Which ship should you choose first? (The one in the middle tells you which half of the line the chosen ship must be in.) Which location would you choose next? (Again the best strategy is always to choose the middle ship of the section that must have the selected ship.) 여러분은 어떤 전함을 가장 먼저 선택했나요? (가운데 있는 전함은 짝이 선택한 전함이 왼쪽 또는 오른쪽에 있다고 말해 줍니다.) 그 다음으로 어떤 전함을 선택했나요? (가장 좋은 전략은 항상 선택된 전함  사이에서 가운데 있는 전함을 고르는 것입니다.)
4. If this strategy is applied how many shots will it take to find a ship? (Five at most). 이런 전략을 선택했다면, 몇 번만에 전함을 찾을 수 있을까요? (최대 5회)

This method is called ‘binary search’, because it divides the problem into two parts.
이런 방법은 문제를 두 개의 부분으로 나누기 때문에 '이진 검색' 이라고 부릅니다.

### Battleships—A Search Game using Hashing 전함 놀이 - 해싱
#### Instructions 설명
1. Each take a sheet as in the previous games and tell your partner the number of your chosen ship. 이전 놀이 방법과 같이 활동지에서 전함을 선택한 후, 짝에게 선택한 전함의 숫자를 말해 줍니다.
2. In this game you can find out which column (0 to 9) the ship is in. You simply add together the digits of the ship’s number. The last digit of the sum is the column the ship is in. For example, to locate a ship numbered 2345, add the digits 2+3+4+5, giving 14. The last digit of the sum is 4, so that ship must be in column 4. Once you know the column you need to guess which of the ships in that column is the desired one. This technique is called ‘hashing’, because the digits are being squashed up (“hashed”) together. 이번 놀이는 어떤 열(0 부터 9)에 전함이 있는지를 찾아내야 합니다. 전함 숫자에서 각 자리수에 해당하는 숫자를 더합니다. 예를 들어, 2345번 전함인 경우 , 2+3+4+5 해서 14를 얻습니다. 14의 1의 자리 수가 4 이므로, 전함은 반드시 4번째 열에 있습니다. 몇 번째 열인지 알았다면, 그 안에서 어떤 전함인지를 추측해야 합니다. 이런 방법은 숫자들이 함께 섞여 있다고 해서('해쉬'), '해싱' 이라고 합니다.
3. Now play the game using this new searching strategy. You may like to play more than one game using the same sheet—just choose from different columns. 이제 새로운 검색 방법으로 놀이를 시작해 봅시다. 다른 열에 있는 전함을 선택하는 방법으로 같은 활동지를 사용하여 여러번 놀이를 할 수 있습니다.

(Note that, unlike the other games, the spare sheets 3A' and 3B' must be used as a pair, because the pattern of ships in columns must correspond.)
(다른 놀이와 다르게, 여분의 활동지인 3A' 과 3B' 은 열에 포함되는 전함의 패턴이 연관되어 있기 때문에 반드시 함께 사용해야 합니다.)

#### Follow Up Discussion 토론하기
1. Collect and discuss scores as before. 이전에 획득한 점수를 모아서 토론해 봅시다.
2. Which ships are very quick to find? (The ones that are alone in their column.) Which ships may be harder to find? (The ones whose columns contain lots of other ships.) 어떤 전함을 빨리 찾을 수 있었나요?(열에 혼자 있는 전함) 어떤 전함이 찾기 어려웠나요? (열에 다른 전함이 많이 포함되어 있음)
3. Which of the three searching processes is fastest? Why? 3가지 검색 방법 중 어떤 방법이 가장 빠른가요? 왜 그런가요?

What are the advantages of each of the three different ways of searching? (The second strategy is faster than the first, but the first one doesn’t require the ships to be sorted into order. The third strategy is usually faster than the other two, but it is possible, by chance, for it to be very slow. In the worst case, if all the ships end up in the same column, it is just as slow as the first strategy.)
3가지 검색 방법의 장점은 각각 무엇인가요? (2번째 전략은 첫 번째 보다 빠르지만, 첫 번째 전략은 전함이 정렬되어 있지 않아도 됩니다. 세번째 전략은 다른 두개의 전략보다 검색이 빠르지만 우연히 매우 느릴 수도 있습니다. 최악의 경우, 모든 배가 같은 열에 있다면 첫 번째 전략 만큼 느립니다.) 

### Extension Activities 추가 활동
1. Have the children make up their own games using the three formats. For the second game they must put the numbers in ascending order. Ask how they might make the Hashing Game very hard. (The hardest game is when all the ships are in the same column.) How could you make it as easy as possible? (You should try to get the same number of ships into each column.) 학생들이 직접 3가지 검색 방법을 사용하는 게임을 각각 만들어 보도록 합니다. 두 번째 게임에서는 숫자를 오름차순으로 정렬해야 합니다. 어떻게 하면 해싱 놀이를 어렵게 만들 수 있을지 물어보세요. (가장 어려운 놀이는 모든 배를 하나의 열에 넣는 것입니다.) 반대로 얼마나 쉽게 놀이를 만들 수 있을까요? (같은 숫자의 전함들을 각각의 열에 넣는 것입니다.)
2. What would happen if the ship being sought wasn’t there? (In the Linear Search game it would take 26 shots to show this. In the Binary Search game you would need five shots to prove this. When using the Hash System it would depend on how many ships appeared in the relevant column.) 찾아야 하는 전함이 없다면 어떻게 될까요? (선형 검색 놀이에서 이 사실을 알기 위해서는 총 26번을 공격해야 합니다. 이진 검색 놀이에서는 이 사실을 증명하기 위해 5번을 공격해야 합니다. 해시 구조를 사용한다면, 관련된 열에 포함된 전함의 수 만큼이 필요합니다.)
3. Using the Binary Search strategy how many shots would be required if there were a hundred locations (about six shots), a thousand locations (about nine), or a million (about nineteen)? (Notice that the number of shots increases very slowly compared to the number of ships. One extra shot is required each time the size doubles, so it is proportional to the logarithm of the number of ships.) 100대의 전함이 있을 때, 이진 검색 전략을 사용하면 몇 번 만에 찾을 수 있을까요? (6번), 1000대의 전함이라면? (9번) 또는 100만대라면? (19번) (전함이 증가하는 것이 비해서 찾을 수 있는 횟수는 천천히 증가합니다. 전함의 수가 두 배로 증가할 때 마다 한 번의 공격 횟수가 증가합니다. 즉, 전함 수의 로그 함수에 비례합니다.)

![image](.../img/ch6/1_kor.png)
![image](.../img/ch6/2_kor.png)
![image](.../img/ch6/3_kor.png)
![image](.../img/ch6/4_kor.png)
![image](.../img/ch6/5_kor.png)
![image](.../img/ch6/6_kor.png)
![image](.../img/ch6/7_kor.png)
![image](.../img/ch6/8_kor.png)
![image](.../img/ch6/9_kor.png)
![image](.../img/ch6/10_kor.png)
![image](.../img/ch6/11_kor.png)
![image](.../img/ch6/12_kor.png)

### What’s it all about? 어떻게 된 거지?
Computers store a lot of information, and they need to be able to sift through it quickly. One of the biggest search problems in the world is faced by Internet search engines, which must search billions of web pages in a fraction of a second. The data that a computer is asked to look up, such as a word, a bar code number or an author’s name, is called a search key.
컴퓨터는 수 많은 정보를 저장하고, 저장된 정보를 빠르게 살펴볼 수 있어야 합니다. 전세계적으로 가장 큰 검색 문제 중 하나는 초당 수십억 개의 페이지를 검색해야 하는 인터넷 검색 엔진에 대한 문제 입니다. 단어나 바코드 숫자, 또는 저자의 이름 등 컴퓨터가 검색하는데 필요한 데이터를 검색 키라고 부릅니다.

Computers can process information very quickly, and you might think that to find something they should just start at the beginning of their storage and keep looking until the desired information is found. This is what we did in the Linear Searching Game. But this method is very slow—even for computers. For example, suppose a supermarket has 10,000 different products on its shelves. When a bar code is scanned at a checkout, the computer must look through up to 10,000 numbers to find the product name and price. Even if it takes only one thousandth of a second to check each code, ten seconds would be needed to go through the whole list. Imagine how long it would take to check out the groceries for a family!
컴퓨터는 매우 빠르게 정보를 처리할 수 있기 때문에, 원하는 정보를 찾을 때 까지 저장공간의 시작부터 끝까지 순서대로 찾을 것이라고 생각할 수 있습니다. 이런 방법은 우리가 선형 놀이에서 했던 방법입니다. 그러나 이런 방법은 심지어 컴퓨터 조차 느립니다. 예를 들어, 슈퍼마켓에 10,000개의 서로 다른 물건이 진열대에 있다고 가정해 봅시다. 계산대에서 물건의 바코드를 검색하면, 컴퓨터는 반드시 10,000개의 물건들 중에서 해당되는 물건의 이름과 가격을 찾아야 합니다. 하나의 바코드를 검색하는데 1/1000 초가 걸린다고 가정하더라도, 모든 물건을 검색하는데 총 10초가 필요합니다. 가족들이 먹을 식료품을 계산하는데 얼마나 걸릴지 상상해 보세요!

A better strategy is binary search. In this method, the numbers are sorted into order. Checking the middle item of the list will identify which half the search key is in. The process is repeated until the item is found. Returning to the supermarket example, the 10,000 items can now be searched with fourteen probes, which might take two hundredths of a second—hardly noticeable.
보다 나은 방법은 이진 검색 입니다. 이 방법에서 숫자는 이미 순서대로 정렬되어 있습니다. 목록의 가운데 물건을 확인함으로써 절반의 물건들 중에 검색키가 있는지 여부를 알 수 있습니다. 원하는 물건을 찾을때 까지 이런 과정을 반복합니다. 슈퍼마켓 예제에서 10,000개의 물건은 14번만에 찾을 수 있으며 이 과정은 총 2/100 초로 거의 알아챌 수 없을 정도 입니다.

A third strategy for finding data is called hashing. Here the search key is manipulated to indicate exactly where to find the information. For example, if the search key is a telephone number, you could add up all the digits in the number and take the remainder when divided by 11. In this respect, a hash key is a little like the check digits discussed in Activity 4—a small piece of data whose value depends on the other data being processed. Usually the computer will find what it is looking for straight away. There is a small chance that several keys end up in the same location in which case the computer will need to search through them until it finds the one it is seeking.
데이터를 찾기 위한 세 번째 검색 전략은 해싱 입니다. 여기에서 검색키는 정보가 어디에 있는지를 정확하게 나타내기 위해 계산됩니다. 예를 들어, 검색키가 전화번호라면 모든 자리의 숫자를 더해서 11로 나눈 나머지를 얻을 수 있습니다. In this respect, 해시키는 활동4(다른 데이터가 처리되기 위해 관련된 작은 데이터 조각)에서 논의한 숫자 검증과 비슷합니다. 일반적으로 컴퓨터는 바로 정보를 찾을 것입니다. 그럴 가능성은 적지만, 몇 개의 해시키가 같은 위치에 생기는 경우 컴퓨터는 각각의 해시키에 해당하는 내용을 검색해야 하므로 검색 시간이 조금 더 걸립니다.

Computer programmers usually use some version of the hashing strategy for searching, unless it is important to keep the data in order, or unless an occasional slow response is unacceptable.
컴퓨터 프로그래머는 데이터를 순서대로 정렬할 필요가 없거나, 느린 검색 결과를 받아들일 수만 있다면 일반적으로 다양한 버전의 해싱 검색 전략을 사용합니다.