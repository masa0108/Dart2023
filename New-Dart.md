# Dart2023
Dart研修
1変数とデータ型

1
void main() {
  int integerVariable = 22;
  
  print(integerVariable);
}

2
void main() {
  String stringVariable = "sato123";
  
  print(stringVariable);
  
}

3
void main() {
  double floatVariable = 3.22;
  
  print(floatVariable);
  }


2 条件分岐 
void main() {
  
 //判定したい整数を入力
 int number = 11;
  
  if(number % 2 == 0){
    print('$numberは偶数です');
  }else{
    print('$numberは奇数です');
  }
  }

3 ループ

void main() {
  for(int i = 1;  i <= 10; i++){
    print(i);
  }
  }

4 関数.

int addNumbers(int a, int b){
  return a + b;
}

void main() {
  int result = addNumbers(10,20);
  print("10と20の加算結果は: $result");
  }

