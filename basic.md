package com.HelloWorld;
import java.util.Scanner;

public class HelloWorld {
	public static void main (String[] args){
		Scanner input=new Scanner(System.in);//创建Scanner对象
		//System.out.println("请输入");
		/*println
		.....
		print ...
		*/
//		String a;
//		a="45456";
//		System.out.println("HWERWER"+a);
//	}


//double avg1=78.5;
//int rise=5;
//double avg2=avg1+rise;
//System.out.println("考试平均分："+avg1);
//System.out.println("调整后的平均分："+avg2);

	
	
	
//		double heightAvg1=176.2;
//		int heightAvg2=(int)heightAvg1;
//		System.out.println(heightAvg1);
//		System.out.println(heightAvg2);
		
	/*	int heightAvg1=176;
		double heightAvg2=(double)heightAvg1;
		System.out.println(heightAvg1);
		System.out.println(heightAvg2);
	
	*/
 /*
		 int a=2;
	    int b=45;
	    int c=a+b;
	    System.out.println(""+c);	
	    	
	    int a=3;
		int b=100;
		int c=b%a;
		System.out.println(""+c);
		  结果1
		
		int a=3;
		int b=100;
		int c=b/a;
		System.out.println(""+c);
		结果33
	*/
		
/*	int a=3;
	int b=++a;//让a 先执行自增，然后将值赋给变量b
	System.out.println(""+b);
	          4
	*/
	
//		int a=3;
//		int b=a++;//将a的值付给b，然后在执行自增
//		System.out.println(""+a);
//		System.out.println(""+b);
		
//		      a=4;
//		      b=3
		      
	    
	/*  int one = 10 ;
        int two = 20 ;
        int three = 0 ;
        
        three=one+two;
        System.out.println("three = one + two ==> "+three);
        three+=one;
        System.out.println("three += one ==> "+three);
        three-=one;
        System.out.println("three -= one ==> "+three);
        three*=one;
        System.out.println("three *= one ==> "+three);
        three/=one;
        System.out.println("three /= one ==> "+three);
        three%=one;
        System.out.println("three %= one ==> "+three); 
        
        4
        3
        three = one + two ==> 30
        three += one ==> 40
        three -= one ==> 30
        three *= one ==> 300
        three /= one ==> 30
        three %= one ==> 0

	*/
		
/*	条件运算符件运算符（ ? : ）也称为 “三元运算符”。
         语法形式：布尔表达式 ？ 表达式1 ：表达式2
                  运算过程：如果布尔表达式的值为 true ，则返回 表达式1 的值，否则返回 表达式2 的值*/
//		public class HelloWorld{
//		    public static void main(String[] args) {
//				int score=68;
//				String mark =(score>60)? "及格":"不及格";
//				System.out.println("考试成绩如何："+mark);
//			}
//		}
	
	/*		int age=25;
	
    if(age>=60){
        System.out.println("老年");
    }else if(age>40){
        System.out.println("中年");
    }else if(age>18){
        System.out.println("少年");
        }
    else{
        System.out.println("童年");
    }
    */
		
		
  /* int score = 63;
		String sex = "女";
        
        if(score>80){
            
            if(sex.equals("女")){
                 
                System.out.println("进入女子决赛");
                 }
                 else{
                     System.out.println("进入男子决赛");
                 }
            
        }
            else{
                System.out.println("淘汰");
            }
            */
	
	/*
	 1、 switch 后面小括号中表达式的值必须是整型或字符型

    2、 case 后面的值可以是常量数值，如 1、2；也可以是一个常量表达式，如 2+2 ；
               但不能是变量或带有变量的表达式，如 a * 2

    3、 case 匹配后，执行匹配块里的程序代码，如果没有遇见 break 会继续执行下一个的 case 块的内容，
                 直到遇到 break 语句或者 switch 语句块结束 如
                  可以把功能相同的 case 语句合并起来，如
                  case 1：
                  case 3：
                  System.out.println("哈哈哈");
    5、 default 块可以出现在任意位置，也可以省略
		char today='日';
		switch(today){
		    case '一':
		    case '三':
		    case '五':
		      System.out.println("包子");
		    break;
		    case '二':
		    case '四':
		    case '六':
		      System.out.println("油条");
		    break;
		    default:
		       System.out.println("主席套餐");
		}
		
//Java循环语句之 while
		int i=1;
		while(i<=100){
		System.out.println(""+i);
		i++;}
			
			
	
//Java循环语句之 do...while  先执行，后判断
		/*语法 do{
			循环操作
		}while(判断条件)；*/
		
	/*int sum = 0; // 保存 1-50 之间偶数的和
        
		int num = 2; // 代表 1-50 之间的偶数
        
		do {
			//实现累加求和
            sum+=num;
            
			num = num + 2; // 每执行一次将数值加2，以进行下次循环条件判断
            
		} while ( num<=50   ); // 满足数值在 1-50 之间时重复执行循环
        
		System.out.println(" 50以内的偶数之和为：" + sum );
	
	*/
	
	// for 关键字后面括号中的三个表达式必须用 “;” 隔开，三个表达式都可以省略，但 “;” 不能省略。

   // a. 省略“循环变量初始化”，可以在 for 语句之前由赋值语句进行变量初始化操作，			
	
       //for(int i=1;i<100 && i!=5; i++){
      //	System.out.println(""+i);
      //}
	
	/*int sum=0;
	for(int i=1;i<=100;i++){
		if(i%3!=0){
			sum=sum+i;
		}
		
	}
	
	System.out.println(""+sum);
	
	*/
	//Break 跳出循环
	
	/*int sum=0;
	for(int i=1;i<=10;i++){
		sum+=i;
		if(sum>=20){
			
			System.out.println(""+sum);
			break;
		}
	}
	*/
		//continue 的作用是跳过循环体中剩余的语句执行下一次循环。
	/*	int sum=0;
		for(int i=1;i<=10;i++){
			if(i%2!=0){
				continue;
				}
			sum+=i;
		}
		System.out.println(""+sum);
	*/
//print就是一般的标准输出，但是不换行

//println和print基本没什么差别，就是最后会换行
		
		//循环嵌套
		/*for(int i=1;i<=9;i++){
			for(int j=1;j<=i;j++){
				System.out.print(j+"*"+i+"="+(i*j)+"  ");	
			}
			System.out.println();
		}
	*/
	

		/* int num = input.nextInt();
		int count = 0;
		if(num>=0 && num<1000000000){
		    while(num!=0){
		        count++;
		        num=num/10;
		    }
		    System.out.println("它是个"+count+"位的数！");
		}else{
		    System.out.println("输入有误！");
		}
		*/
		
	/*	do
          {
            count++;
            num=num/10; 
           }
             while(num >0);

           System.out.println("它是个" + count + "位的数！");

		 int num = 5985965;
			int count = 0;
	*/
		
		 /* for(;;){
	            count++;
	            num = num / 10;
	            if(num == 0)
	                break;
	        }
	        System.out.println("它是个"+count+"位的数！");
	    
	*/
		/*int sum=0;
		for(int i=1;i<=100;i++){
			if(i%3==0 && i%5==0){
				sum+=i;}
			
		}
		System.out.println("1~100的和是："+sum);
	   */
//	  int sum=0;
//	  int i=0;
//	  if(i%2==0 ){
//	   while(i<=100){
//		   sum+=i;
//		    i++;
//	   }
//	 
//	   System.out.println("1~100的和是："+sum);
//	  }
//	  }
	  
	/*int sum=0;
	int i=1;
	while(i<=100){
		if(i%2==0){
	sum+=i;
	}
	i++;
	}
	System.out.println("1~100偶数之和是："+sum);
	*/
	/*for(int i=1;i<=100;i++){
		if(i%3==0){
			System.out.println("100以内能被三整除得数是:"+i);
		}
	}
	*/

		/*int score=input.nextInt();
		int count=0;
		System.out.println("加分前："+score);
		while(score<=60){
			score+=1;
			count++;
		}
		System.out.println("加分后成绩："+score);
		System.out.println("加分次数："+count);
		*/
		
	/*	int score=53;
		int count=0;
		System.out.println("加分前："+score);
		do{
			score+=1;
			count++;
		}while(score<60);
			
			System.out.println("加分后成绩："+score);
		System.out.println("加分次数："+count);
	*/
		/*int score=53;
		int count=0;
		System.out.println("加分前："+score);
		//可无  if(score<60){     
	//注意 循环变量操作和循环操作之间     ,
		for(;score<60;score++,count++){
			//count++;
		}System.out.println("加分后成绩："+score);
		System.out.println("加分次数："+count);
		*///}
		/*int score=53;
		int count=0;
		  if(score>=60){
		         System.out.println("成绩合格：");
		    }else{
		        while(score<60){
		          score++;
		         count++;
		     }
		    }
		        
		        
		        
		        System.out.println("加分后成绩："+score);
		        System.out.println("加分次数"+count);
		        //打印输出加分后成绩，以及加分次数
		     */
		//功能: 实习先接受三个班级的个四名学员的成绩，然后计算每个班级学员平均分
		//知识点：二重循环，外层控制班级的数量，内层每个班级的学员数量
		/* int classNum=3;
		 int stuNum=4;
		 double sum=0;
		double avg=0;
		
		//Scanner input =new Scanner(System.in);//创建Scanner对象
		for(int i=1;i<=classNum;i++){//外层控制 班级数量
			sum=0;//防止每个班级混合
			System.out.println("请输入第"+i+"个班级的成绩");
			for(int j=1;j<=stuNum;j++){
				System.out.println("请输入第"+j+"个学员的成绩");
				int score=input.nextInt();//获取输入成绩
				sum+=score;//成绩累计求和
				
			}
			avg=sum/stuNum;
			System.out.println("第"+i+"个班级学生的平均分为："+avg);
		}*/
		for(int i=1;i<=9;i++){
			for(int j=1;j<=i;j++){
				System.out.print(i+"*"+j+ "="+ i*j+"  ");
			}System.out.println();
		}
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	
	}}
