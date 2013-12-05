labhw
=====

public class cards {
	String rank; String suit;
	
	public static void main (String [] args)
	{
		cards c1 = new cards ("Q","Hearts");
		cards c2 = new cards ("10","Hearts");
	}
	
	public cards (String r, String s)
	{
		rank = r;
		suit = s;
	}

	public String rank()
	{
		String [] rank = {"2","3","4","5","6","7","8","9","10","J","Q","K","A"};
		return null;
		
	}
	public String suit ()
	{
		String [] suit = {"Clubs", "Diamonds","Hearts", "Spades"}; 
		return null;
		
	}
	public boolean isOfSuit(String c)
	{
		return c.equals(suit);
		
	}
	public boolean stronger (cards c)
	{
		if (c.equals(rank))
			if (c.suit() > ) 
				
		
	}
	
	public String toString ()
	{
		return null;
		
	}
	
	
}
