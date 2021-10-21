import java.io.*;
import java.util.*;

public class Main {

    public static void main(String[] args) throws Exception {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int m=sc.nextInt();
        int arr[][]=new int[n][m];
        for(int i=0;i<n;i++)
        {
            for(int j=0;j<m;j++)
            {
                arr[i][j]=sc.nextInt();
            }
        }
        int dir=0,i=0,j=0;
        while(i<n && j<m)
        {
            dir=(dir+arr[i][j])%4;
            if(dir==0)
            {
                j++;
            }
            if(dir==1)
            {
                i++;
            }
            if(dir==2)
            {
               j--; 
            }
            if(dir==3)
            {
               i--; 
            }
        }
        if(i<0)
        {
            i++;
        }
        if(j<0)
        {
            j++;
        }
        if(i==n)
        {
            i--;
        }
        if(j==m)
        {
            j--;
        }
        System.out.println(i);
        System.out.println(j);
    }

}
