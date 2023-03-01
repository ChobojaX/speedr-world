# speedr-world
ok this is devel backup powered by fastback


### 월드 적용 방법
1. 왼쪽 위 부근에 있는 main 버튼을 누른 후 View all branches 를 누른다.
2. 원하는 날짜의 백업본을 선택한다. (snapshots/beb405da-1b94-4c3a-a4bc-9e7583da0c1a/ 으로 시작하는 걸 골라야 한다.)
3. 오른쪽 위의 초록색의 Code 버튼을 누르고 Download Zip 버튼을 누른다.
4. 마인크래프트 월드가 다운받아진다. 폴더 이름은 알아서 정하셈.

### 데이터팩 적용 방법
 - 왜인진 몰라도 데이터팩 부분은 이 저장소에 포함되지 않습니다. 따라서 이 월드를 사용하실 때에는 데이터팩을 수동으로 적용시켜줘야 합니다.
1. [데이터팩](https://github.com/ChobojaX/speedr) 저장소로 간다.
2. 오른쪽 위의 초록색의 Code 버튼을 누르고 Download Zip 버튼을 누른다.
3. 가장 최신버젼의 데이터팩이 다운받아진다. **데이터팩의 상태와 월드의 상태가 항상 같지는 않으므로 몇몇 기능이 나사빠져있다면 개발자에게 업데이트하라고 요구를 하면 된다.**
4. 이를 `월드 폴더 최상위 위치`/datapacks/ 에 압축을 푼다. **폴더의 이름을 speedr로 바꿔야 작동한다.**

### 이렇게 까지 해야하나?
고도의 삽질을 한 결과 그렇다. submodule로 관리를 해도 일반인들이 git을 사용할
이유가 없다. 그런데 git을 안쓰면 다운로드할때 데이터팩이 안딸려온다.
