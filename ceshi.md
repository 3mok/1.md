# 作为软件开发人员，为什么要编写单元测试？
单元测试是由程序员自己来完成，最终受益的也是程序员自己。可以这么说，程序员有责任编写功能代码，
同时也就有责任为自己的代码编写单元测试。执行单元测试，就是为了证明这段代码的行为和我们期望的一致。
# 实现冒泡排序
 package maopao;
 public class maopaopao{
 public static void main(String[] args) {
		 int [] arry = {3,9,2,1,54,65,8989,51};
		 for(int i = 0 ; i < arry.length-1 ; i++) {
			 for(int j = 0 ; j < arry.length - i-1 ; j++) {
				 if(arry[j] > arry[j+1]) {
					 int t = arry[j];
					 arry[j] = arry[j+1];
					 arry[j+1] = t;
				 }
			 }
		 }
		 for(int i = 0 ; i <arry.length ; i++) {
			 System.out.print(arry[i]+" ");
		 }
	}
}
