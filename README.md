# OOP2026

### Homework1

```java

public class HelloWorld {
    public static void main(String []args){
       for(int i=0; i<10; i++) {
           for(int j=0; j<=i; j++) {
               System.out.print("#");
       }
           for(int j=i; j<10; j++) {
               System.out.print(" ");
           }
          
           System.out.println();
   }
   for(int i=0; i<10; i++) {
           for(int j=0; j<=i; j++) {
               System.out.print("");
       }
           for(int j=i; j<10; j++) {
               System.out.print("#");
           }
           System.out.println();
   }
   for(int i=10; i>0; i--) {
           for(int j=0; j<=i; j++) {
               System.out.print(" ");
       }
           for(int j=i; j<10; j++) {
               System.out.print("#");
           }
           System.out.println();
   }
  for(int i=0; i<10; i++) {
           for(int j=0; j<=i; j++) {
               System.out.print(" ");
       }
           for(int j=i; j<10; j++) {
               System.out.print("#");
           }
           System.out.println();
   }
    }


}
```


### Homework2

```java
public class pivo {
	public static void main(String []args){
	int a = 1, b = 1, c;
		System.out.print("1 1 ");

		for(int i=0; i<18; i++) {
			c = a + b;
			System.out.print(c+" ");
			a = b;
			b = c;
		}  
	}	
}
```



### Homework3

```java
public class golden_ratio{
	public static void main(String []args) {
		double a=1 ,b=1, ratio;
		
		for(int i =0;i<20;i++)
		{
			ratio = a+b;
			System.out.printf("%.8f \n", ratio/a);
			b=a;
			a=ratio;
		}
	}
	
}
```


### Homework4

```java
public class multiplication_table {
	public static void main(String []args) {
		for(int i=1;i<10;i++) {
			for(int j=1;j<10;j++) {
				System.out.printf("%d*%d=%d ",j,i,j*i);
			}
			System.out.println();
		}
	}
}
```


