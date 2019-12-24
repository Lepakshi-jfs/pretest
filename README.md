# pretestimport java.util.*;
public class ReverseString
{
    public static void main(String[] args)
    {   int count=0;
      
        System.out.println("Enter string to reverse:");
        
        Scanner read = new Scanner(System.in);
        String str = read.nextLine();
        String reverse = "";
        
        
        for(int i = str.length() - 1; i >= 0; i--)
        {
            reverse = reverse + str.charAt(i);
        }
        
        System.out.println("Reversed string is:");
        System.out.println(reverse);
       for (int i=0 ; i<str.length(); i++){
         char ch = str.charAt(i);
         if(ch == 'a'|| ch == 'e'|| ch == 'i' ||ch == 'o' ||ch == 'u'||ch == ' '){
            count ++;
         }
      }
      System.out.println("Number of vowels in the given sentence is "+count);
        
    }
}

