//Bruno Sousa

import javax.swing.JOptionPane; 
import java.util.ArrayList; 
import java.util.Collections; 
 public static void main(String[] args) { 
 ArrayList<String> names = new ArrayList<String>(); 
 String tmp; 
 int vowels = 0; 
 int Char = 0 ; 
 char c; 
 
 
 tmp = JOptionPane.showInputDialog("Enter a name, Press 
enter to end."); 
 
 for (int i =0; i < tmp.length();) { 
 for (int j = 0; j < tmp.length(); j++ ) { 
 
 c = tmp.charAt(j); 
 
 
 if (tmp.charAt(j) == 'a' || tmp.charAt(j) == 'e' || 
tmp.charAt(j) == 'i' 
 || tmp.charAt(j) == 'o' || tmp.charAt(j) == 
'u' || tmp.charAt(j) == 'A' || tmp.charAt(j) == 'E' || 
tmp.charAt(j) == 'I' 
 || tmp.charAt(j) == 'O' || tmp.charAt(j) == 
'U') 
 { 
 vowels++; 
 } 
 if(tmp.charAt(i) != ' ') { 
 Char++; 
 
 } 
 
 } 
 
 tmp = ("- " + tmp + " Contains: " + vowels + " vowels"+ " 
and " + Char + " constants." + " \n" ); 
 names.add(tmp.toString()); 
 Collections.sort(names); 
 names.sort(String.CASE_INSENSITIVE_ORDER); 
 tmp = JOptionPane.showInputDialog("Enter a name, Press 
enter to end."); 
 
 
 vowels = 0; 
 Char = 0; 
 } 
 System.out.println(names);{ 
 } 
 } 
