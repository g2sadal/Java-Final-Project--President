# Java-Final-Project--President

import java.util.List;

public class Player extends Thread
{
    private List<Cards> hand;
    private int rank;
    
    private Player ()
    {
    }
    
    private void selectCard()
    {  
    }
    
    private Card playCard(/*card index sent from display/game */int i)
    {
        return hand.remove(i);
    }
        
    private void pass()
    {
        //called in display or game
        //disables players game buttons
        //increments current turn in game
    }
    
    
}
