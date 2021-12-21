# automation7import java.util.Arrays;

public class duplicatenum {
	public static void main(String[] args) {

int[] a= {20,20,25,40,50,60,70,70,80,80,};
boolean flag = false;

for(int i=0;i<=a.length;i++) {
	for(int j=i+1;j<=a.length-1;j++) {
		if(a[i]==a[j]) {
			System.out.println("duplicate value is "+a[i]);
			 flag = true;
		} 
	}
	
}if(flag==false) {
	System.out.println("not duplicate");
}
