public class Main
{
	public static void main(String[] args) 
	{
        int[] summ = new int [10];
		int[][] array = new int[8][8];
		
		for(int i=0; i<array.length; i++)
		{
		    for(int j=0;j<array[i].length;j++)
		    {
    		    if((Math.abs(i-j))%2==0)
    		    {
    		         array[i][j]=1;
    		    }
		        else
		        {
		            array[i][j]=0;
		        }
		    }
		}
		for(int i=0; i<array.length; i++)
		{
		    for(int j=0;j<array[i].length;j++)
		    {
		        System.out.print(array[j][i] + " ");
		    }
            System.out.print("\n");
		}
		
		int[][] array2 = new int[10][10];
		System.out.print("\n");
		
		for(int i=0; i<array2.length; i++)
		{
		    for(int j=0;j<array2[i].length;j++)
		    {
		        array2[i][j] = (int)(Math.random()*50-25 );
		    }
		}
		for(int i=0; i<array2.length; i++)
		{
		    for(int j=0;j<array2[i].length;j++)
		    {
		        System.out.print(array2[j][i] + "\t ");
		    }
		}
		
		for(int i=0; i<array2.length; i++)
		{
		    for(int j=0;j<array2[i].length;j++)
		    {
		    summ[i] += array2[j][i];
		    }
		}
		for(int i=0; i<array2.length; i++)
		{
		    System.out.println("Сумма " + (i+1) + " строчки = " + summ[i]);
		}
		
		int prost = 0;
		int k = 0;
		System.out.println("\n Простые числа: ");
		
		for(int i=0; i<array2.length; i++)
		{
		    for(int j=0;j<array2[i].length;j++)
		    {
		        if (array2[i][j]>=3)
		        {
    		        for(int g=2; g<array2[i][j];g++)
    		        if(array2[i][j]%g==0)
    		        {
    		            k++;
    		        }
    		        if(k==0){
		            System.out.print(array2[i][j] + " ");
		        }
		        if(array2[i][j]==2){
		            System.out.print(array2[i][j] + " ");
		        }

		        }
		        k=0;
		    }
		}
		
	}
}
