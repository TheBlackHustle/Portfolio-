public static void main(String[] args) {
	final int NUM_UPPER_LETTERS = 2;
	final int NUM_LOWER_LETTERS = 3;
	final int NUM_DIGITS = 1;
	int upperCount = 0;
	int lowerCount = 0;
	int digitCount = 0;
	int letterCount = 0;
	
	Scanner scan = new Scanner(System.in);
	
	System.out.println("Enter your password...");
	System.out.println("Password must have:");
	System.out.print(", 2 uppercase letters");
	System.out.print(", 2 lowercase letters");
	System.out.print(", 1 digit.");
	System.out.println(" ");
	System.out.println("Enter your password:");
	 
	String input = scan.nextLine();

	int inputLen = input.length();
	
	for (int i = 0; i < inputLen; i++) {
		char ch = input.charAt(i);
		if (Character.isUpperCase(ch))
				upperCount++; 
		else if (Character.isLowerCase(ch))
			lowerCount++;
		else if (Character.isDigit(ch))
			digitCount++;
		
	}
		if (upperCount >= NUM_UPPER_LETTERS && lowerCount >= NUM_LOWER_LETTERS && digitCount >= NUM_DIGITS)
			System.out.println("Valid Passord.");
		else {
			System.out.println("The password you entered did not have enough of the following criteria");
			if (upperCount < NUM_UPPER_LETTERS)
				System.out.println("uppercase letters.");
			if (lowerCount < NUM_LOWER_LETTERS)
				System.out.println("lowercase letters.");
			if (digitCount < NUM_DIGITS)
				System.out.println("digits");
			
			
		}
}
}
