```c++偏门题
1.

int i=0;
void main(){
  int i=i;
}
问：输出结果是什么？
答案：main()里面的i是一个未定义值

2.赋值顺序:右向左
int x=2,y,z;
x*=(y=z=5);

x=?
```
