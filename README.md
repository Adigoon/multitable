# multitable
multiplication table
package Yabo;
import static java.lang.System.out;
public class multiTable {

	public static void main(String[] args) {
		int rows, columns;
		
		
			
		for (rows = 1; rows <= 9; rows++) {
			
		for (columns = 1; columns <= 9; columns++) {
			
				out.print(rows * columns + "\t");
			
		}
		out.println();
			}
		
}
	
}
