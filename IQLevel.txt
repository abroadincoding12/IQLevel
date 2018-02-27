import javax.swing.JOptionPane;
public class IQLevel
{

	public static void main(String[] args)
	{
		int iq;
		String input;

		final double IQ_LEVEL1 = 69;  //You are borderline stupid
		final double IQ_LEVEL2 = 84;  //You are below average
		final double IQ_LEVEL3 = 114; //You are average
		final double IQ_LEVEL4 = 129; //You are above average
		final double IQ_LEVEL5 = 144; //You are highly intelligent
		final double IQ_LEVEL6 = 145; //You are a genius

		input = JOptionPane.showInputDialog("Enter your IQ level ");
		iq = Integer.parseInt(input);

		if (iq <= IQ_LEVEL1)
		{
			JOptionPane.showMessageDialog(null, "You are borderline stupid");
		}

		else if (iq <= IQ_LEVEL2)
		{
			JOptionPane.showMessageDialog(null, "You are below average");
		}

		else if (iq <= IQ_LEVEL3)
		{
			JOptionPane.showMessageDialog(null, "You are average");
		}

		else if (iq <= IQ_LEVEL4)
		{
			JOptionPane.showMessageDialog(null, "You are above average");
		}

		else if (iq <= IQ_LEVEL5)
		{
			JOptionPane.showMessageDialog(null, "You are highly intelligent");
		}

		else if (iq >= IQ_LEVEL6)
		{
			JOptionPane.showMessageDialog(null, "You are a genius");
		}

		System.exit(0);

	}
}