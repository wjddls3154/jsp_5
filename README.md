# jsp_5 : and, or, not 연산자

![image](https://user-images.githubusercontent.com/37132897/158109458-f1e3874a-8d2f-4f0f-9479-197190382c04.png)
- x(true) && y(false), false 가 출력된다 : and(&)는, 값이 모두 true 여야 true 값 출력
- x(true) || y(false), ture 가 출력된다 : or(|)는, 값중 하나만 true 이면 true 값 출력
- y는 false이고, y!(false의 not은 true), 그러므로 true 가 출력된다.

      // 변수 
      
      var x, y;
      
      x = true; // true 이면, 1의 값이 출력된다.
      
      y = false; // false 이면, 0의 값이 출력된다.
      
      // 변수 이용한 and,or,not연산자
      
      document.write("1: ", x && y); // and
      
      document.write("<br>");
      
      document.write("2: ", x || y); // or
      
      document.write("<br>");
      
      document.write("3: ", !y); // not
      
      document.write("<br>");
