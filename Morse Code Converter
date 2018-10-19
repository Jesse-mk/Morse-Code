/**
 * 
 */

/**
 * @author jesse
 *
 */
import java.util.Scanner;

public class morseCode {
	private static String letters(char letter){
		switch(letter){
		case 'A': return ".-";
		case 'B': return "-...";
		case 'C': return "-.-.";
		case 'D': return "-..";
		case 'E': return ".";
		case 'F': return "..-.";
		case 'G': return "--.";
		case 'H': return "....";
		case 'I': return "..";
		case 'J': return ".---";
		case 'K': return "-.-";
		case 'L': return ".-..";
		case 'M': return "--";
		case 'N': return "-.";
		case 'O': return "---";
		case 'P': return ".--.";
		case 'Q': return "--.-";
		case 'R': return ".-.";
		case 'S': return "...";
		case 'T': return "-";
		case 'U': return "..-";
		case 'V': return "...-";
		case 'W': return ".--";
		case 'X': return "-..-";
		case 'Y': return "-.--";
		case 'Z': return "--..";
		case ' ': return "  ";
		default: return "invalid morse code";
		}	
	}
	
	public static String morseCode(String convert){
		String sentence= "";
		for(int i=0; i<convert.length(); i++){
			String add = letters(convert.charAt(i));
			sentence += add+ " ";
		}
		return sentence;
	}
	
	
	/**
	 * @param args
	 */
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner first = new Scanner(System.in);
		while(first.hasNext()){
			String putIn = first.next()+" ";
			System.out.print(morseCode(putIn.toUpperCase()));
		}
	}

}
