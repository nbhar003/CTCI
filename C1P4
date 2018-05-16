package plswork;

public class pls2 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		String s1 = "tat";
		String s2 = "tac";
		int [] asciiarr = new int [256];
		boolean anagram = true; 
		if (s1.length() != s2.length()) {
			System.out.println("This is not an anagram");
		}
		
		else {
			for (int i = 0; i < s1.length(); i++) {
				int value = s1.charAt(i);
				asciiarr[value]++;
			}
			
			for (int i = 0; i < s2.length();  i++) {
				int value = s2.charAt(i);
				asciiarr[value]--;
				if (asciiarr[value] < 0) {
					anagram = false; 
					break;
				}
			}	
			System.out.println(anagram); 
		}
	}

}
