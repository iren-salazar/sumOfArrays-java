# sumOfArrays-java
/*Write a function that takes an array of numbers (integers for the tests) and a target number. It should find two different items in the array that, when added together, give the target value. The indices of these items should then be returned in a tuple / list (depending on your language)  like so: (index1, index2).*/


public class arraynums {
	public static void main(String[] args)  
		{
			int arr [] = {3,2};
			sum (arr);
		}
		public static void sum (int arr[])
		{
			int sum =0;
			
			for (int i = 0; i < arr.length; i++)
				sum += arr [i];
			
			System.out.println("sum " + sum);
		}
}
