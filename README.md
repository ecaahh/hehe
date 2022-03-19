import javax.swing.*;
import java.awt.*;
import java.applet.Applet;
 
public class Simple
{
 
   public static void main(String[] args)
   {
       JFrame game = new JFrame("Code Breaker!");
       JPanel p1 = new JPanel();
       game.setContentPane(p1);
       p1.setLayout(null);
       Picture empty = new Picture("Empty.png");
 
       JPanel p = new JPanel(new GridLayout(6,4));
       JPanel p2 = new JPanel(new GridLayout(12,2));
       JPanel p3 = new JPanel(new GridLayout(1,7));
       BorderLayout layout = new BorderLayout();
       p1.setLayout(layout);
       p1.add("Center", p);
       p1.add("East", p2);
       p1.add("South", p3);
 
 
       JLabel l1 = new JLabel(empty);
       p.add(l1);
 
       JLabel l2 = new JLabel(empty);
       p.add(l2);
        JLabel l3 = new JLabel(empty);
       p.add(l3);
     
       JLabel l4 = new JLabel(empty);
       p.add(l4);
 
       JLabel l5 = new JLabel(empty);
       p.add(l5);
  
       JLabel l6 = new JLabel(empty);
       p.add(l6);
 
       JLabel l7 = new JLabel(empty);
       p.add(l7);
 
       JLabel l8 = new JLabel(empty);
       p.add(l8);
 
       JLabel l9 = new JLabel(empty);
       p.add(l9);
 
       JLabel l10 = new JLabel(empty);
       p.add(l10);
 
       JLabel l11 = new JLabel(empty);
       p.add(l11);
 
       JLabel l12 = new JLabel(empty);
       p.add(l12);
 
       JLabel l13 = new JLabel(empty);
       p.add(l13);
 
       JLabel l14 = new JLabel(empty);
       p.add(l14);
 
       JLabel l15 = new JLabel(empty);
       p.add(l15);
 
       JLabel l16 = new JLabel(empty);
       p.add(l16);
 
       JLabel l17 = new JLabel(empty);
       p.add(l17);
 
       JLabel l18 = new JLabel(empty);
       p.add(l18);
 
       JLabel l19 = new JLabel(empty);
       p.add(l19);
 
       JLabel l20 = new JLabel(empty);
       p.add(l20);
 
       JLabel l21 = new JLabel(empty);
       p.add(l21);
 
       JLabel l22 = new JLabel(empty);
       p.add(l22);
 
       JLabel l23 = new JLabel(empty);
       p.add(l23);
 
       JLabel l24 = new JLabel(empty);
       p.add(l24);
  
       JLabel s1 = new JLabel(empty);
       p2.add(s1);
 
       JLabel s2 = new JLabel(empty);
       p2.add(s2);
        JLabel s3 = new JLabel(empty);
       p2.add(s3);
     
       JLabel s4 = new JLabel(empty);
       p2.add(s4);
 
       JLabel s5 = new JLabel(empty);
       p2.add(s5);
  
       JLabel s6 = new JLabel(empty);
       p2.add(s6);
 
       JLabel s7 = new JLabel(empty);
       p2.add(s7);
 
       JLabel s8 = new JLabel(empty);
       p2.add(s8);
 
       JLabel s9 = new JLabel(empty);
       p2.add(s9);
 
       JLabel s10 = new JLabel(empty);
       p2.add(s10);
 
       JLabel s11 = new JLabel(empty);
       p2.add(s11);
 
       JLabel s12 = new JLabel(empty);
       p2.add(s12);
 
       JLabel s13 = new JLabel(empty);
       p2.add(s13);
 
       JLabel s14 = new JLabel(empty);
       p2.add(s14);
 
       JLabel s15 = new JLabel(empty);
       p2.add(s15);
 
       JLabel s16 = new JLabel(empty);
       p2.add(s16);
 
       JLabel s17 = new JLabel(empty);
       p2.add(s17);
 
       JLabel s18 = new JLabel(empty);
       p2.add(s18);
 
       JLabel s19 = new JLabel(empty);
       p2.add(s19);
 
       JLabel s20 = new JLabel(empty);
       p2.add(s20);
 
       JLabel s21 = new JLabel(empty);
       p2.add(s21);
 
       JLabel s22 = new JLabel(empty);
       p2.add(s22);
 
       JLabel s23 = new JLabel(empty);
       p2.add(s23);
 
       JLabel s24 = new JLabel(empty);
       p2.add(s24);
  
 
       Picture Colour_0 = new Picture("Colour_0.png");
       JButton l0 = new JButton(Colour_0);
       p3.add(l0);
      
 
       Picture Colour_1 = new Picture("Colour_1.png");
       JButton l1 = new JButton(Colour_1);
       p3.add(l1);
      
      
       Picture Colour_2 = new Picture("Colour_2.png");
       JButton l2 = new JButton(Colour_2);
       p3.add(l2);
      
       Picture Colour_3 = new Picture("Colour_3.png");
       JButton l3 = new JButton(Colour_3);
       p3.add(l3);
      
       Picture Colour_4 = new Picture("Colour_4.png");
       JButton l4 = new JButton(Colour_4);
       p3.add(l4);
      
       Picture Colour_5 = new Picture("Colour_5.png");
       JButton l5 = new JButton(Colour_5);
       p3.add(l5);
      
       Picture Colour_6 = new Picture("Colour_6.png");
       JButton l6 = new JButton(Colour_6);
       p3.add(l6);
 
       game.setSize(500,660);
       game.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
       game.setVisible(true);
 
 
 
 
   }
 
}
 
 
