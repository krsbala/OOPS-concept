# OOPS-concept
class Calculator {
    int num1;int num2;
    Calculator(int a,int b){
        num1=a;
        num2=b;
    }
    void add(){
        System.out.println("Addition:"+(num1+num2));
    }
    void sub(){
        System.out.println("Subration:"+(num1-num2));
    }
    void mult(){
        System.out.println("Multiplication:"+(num1*num2));
    }
    void div(){
        System.out.println("Division:"+(num1/num2));
    }
}

public class Main
{
	public static void main(String[] args) {
	    Calculator calc=new Calculator(10,3);
	    calc.add();
	    calc.sub();
	    calc.mult();
	    calc.div();
		
	}
}
