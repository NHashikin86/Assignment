# Assignment

package assignment1;

import java.io.FileNotFoundException;
import java.io.PrintWriter;
import java.io.UnsupportedEncodingException;

public class Assignment1 {

     public static void main(String[] args) throws FileNotFoundException, UnsupportedEncodingException {
       try (
               /**File location for assignment 
                * 
                */
       PrintWriter writer = new PrintWriter("C:\\Users\\User\\Documents\\Test\\NurHashikinAssign1.txt")) {
               writer.println("Name : Nur Hashikin Abd Karim");
               writer.println("Matrix No : 2014224714");
               writer.println("Gender: Female");
               writer.println("Age : 29");
               writer.println("Email : ieykin.abdul@gmail.com");
               writer.println("Mobile Phone : 012 2208258");
    
    
            
    }
    
}
}
