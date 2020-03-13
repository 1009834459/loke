tsc -w 1.ts  //跟踪监控变化

let name:string = 'whh';
let greeting:string ='yo ${name}';

console.log(greeting);        //${}插入变量

void 空类型
可用 null ,undefined
数组:Array<类型all,number等>=[*,*,*]

元组:[number,number,number]   元组限定了数量和类型

enum 枚举类型
enum sizi {L=10,M=100,S} 一次sizi只能引用一个,限制对象的

class 定义类
extends 扩充泪
class Student extends Person{   //继承了Person的内容

}

super()  调用父级的类

Interface 接口,限制对象和函数

interface User{
    name:string,// 必填
    age:number,// 必填
    gender?: string, // 可选
    [key:string]:any any // 其他属性
}

用接口限制函数

/**
 * 函数接口
 */
interface UserFunction {
  /**
   * @param name
   * @param age
   */
  (name: string, age: number): void;
}

let createUser: UserFunction = (name, age) => {
  console.log(name, age);
}

createUser('王花花', 18);