# JavaProject 메모!

**Project01-가위바위보 게임**<br>
//난수를 얻어내는 방법<br>
1. Random 클래스 활용<br>
-Random r = new Random();<br>
_1.1 Random 클래스 주요 메소드<br>_
-double nextDouble: double 타입의 난수를 리턴<br>
-int nextInt(): int타입의 난수를 리턴<br>
-int nextInt(int n): int타입의 0~매개값까지의 난수를 리턴<br>
<br>

**Project02-영화좌석예매**<br>
//버튼마다 기능 달아주기<br>
```
buttins[i] addActionListener(new ActionListener() {
				
  @Override
  public void actionPerformed(ActionEvent e) {
    }
