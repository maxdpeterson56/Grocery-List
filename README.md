# Grocery-List
* This program calculates the price of 9 items as entered by the user. 
package grocerylist;
import java.util.Scanner;
/**
 *
 * @author Max Peterson
 */
public class GroceryList {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        double [] prices = new double [9];
        Scanner in = new Scanner(System.in);
        System.out.println ("Enter 9 prices: ");
        prices [0] = in.nextDouble ();
        prices [1] = in.nextDouble ();
        prices [2] = in.nextDouble ();
        prices [3] = in.nextDouble ();
        prices [4] = in.nextDouble ();
        prices [5] = in.nextDouble ();
        prices [6] = in.nextDouble ();
        prices [7] = in.nextDouble ();
        prices [8] = in.nextDouble ();
        double total = prices[0] + prices[1] + prices[2] + prices[3] + prices[4] + prices [5] + prices [6] + prices [7] + prices [8];
        System.out.printf ("The total for all 9 items is:$%5.2f ", total);
    }
    
}
