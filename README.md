import java.util.Random;

public class ComputeMethods5026211184 {

	public double fToC(double degreesF){
		return 5.0/9.0*(degreesF-32);
	}
	public double hypotenuse(int a, int b) {
		return Math.sqrt((a * a) + (b * b));
	}
	public int roll(){
		Random rndm = new Random();
		int dice1 = rndm.nextInt(6)+1;
		int dice2 = rndm.nextInt(6)+1;

		return dice1 + dice2;
	}
}
