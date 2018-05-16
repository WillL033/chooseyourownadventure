# chooseyourownadventure
role playing game
package rpg;
import java.util.Scanner;
public class OneWordTextGame {
	private String Name;
	private String destination;
	private static String game = "Start";
	private int Health;
	private int Damage;
	private int Coin;
	/*public static final String BLACK = "\033[0;30m";   // BLACK
	public static final String RED = "\033[0;31m";     // RED
	public static final String GREEN = "\033[0;32m";   // GREEN
	public static final String YELLOW = "\033[0;33m";  // YELLOW
	public static final String BLUE = "\033[0;34m";    // BLUE
	public static final String PURPLE = "\033[0;35m";  // PURPLE
	public static final String CYAN = "\033[0;36m";    // CYAN
	public static final String WHITE = "\033[0;37m";   // WHITE */

	public void Character(int HP, int DMG, int C) {
		Health = HP;
		Damage = DMG;
		Coin = C;
	}
	public static void main(String[] args) throws InterruptedException {

		Scanner choices = new Scanner(System.in);
		System.out.println();
		System.out.println(" Hello Adventurer! Welcome to the T.O.A, the Text Oriented Adventure. ");
		while(game.equals("Start")) {
			System.out.println(" ___________________________________________________________________________________ ");
			System.out.println(" ~Rules~ ");
			System.out.println(" 1. Only ONE word please" );
			System.out.println(" 2. Don't turn around when facing a monster" );
			System.out.println(" 3. And Spell Correctly " );
			System.out.println(" 4. Options are in brackets");
			System.out.println(" Understand?  [Yes or No]" );
			System.out.println("___________________________________________________________________________________");
			String begin = choices.next();


			if(begin.equals("Yes")|| begin.equals("yes")) {
				System.out.println("___________________________________________________________________________________");
				System.out.println(" What will your name be? ");

				String name = choices.next();
				System.out.println("___________________________________________________________________________________");
				System.out.println("Welcome " + name + ". Which role would you like to play as? [Melee or Range]");



		while(begin.equals("Yes") || begin.equals("yes")) {
			String role = choices.next();
			if(role.equals("Melee") || role.equals("melee")) {
				System.out.println("	    ______________________________________  ");
				System.out.println("	   | As a melee, you have 200HP and 10 DMG|  ");
				System.out.println("	   | Here's a wooden sword                |  ");
				System.out.println("	   | ~ Obtains Wooden Sword ~             |  ");
				System.out.println("	   |______________________________________|  ");
				int HP = 200;
				int DMG = 10;
				System.out.println();
				System.out.println(" ~ Forest of the Beginning ~ ");
				System.out.println(" You wake up in the middle of a field. There are 2 trails \nChoose a route [Left] or [Right]");
				while(role.equals("melee")||role.equals("Melee")||role.equals("Range")||role.equals("range")) {
					String direction = choices.next();












		//William's Work	
		if(direction.equals("Left")||direction.equals("left")) {
			System.out.println("___________________________________________________________________________________");
			System.out.println("You walk down the Quiet Trail. \nYou encounter a Green Slime [40HP and 5 DMG] \nWhat will you do? [Fight] or [Run]");
			System.out.println("___________________________________________________________________________________");
			while(direction.equals("left") || direction.equals("Left")) {
				String actions = choices.next();
				while(direction.equals("left")||direction.equals("Left")) {

					if(actions.equals("Fight")||actions.equals("fight")) {

						while(actions.equals("Fight")||actions.equals("fight")) {
							System.out.println("[ " + HP + "HP " + DMG + " DMG ]" + "\nYou engaged in a fight with the slime (Fighting...)");
							Thread.sleep(3250);
							
							System.out.println("");
							System.out.println("[-40 CRIT] The slime burst into tiny pieces... [+15 coins]");
							System.out.println(" Continues Walking... (Please Wait)");
							Thread.sleep(4750);
							System.out.println("___________________________________________________________________________________");
							System.out.println();
							System.out.println(" You've made it to town \n~ParamTown~" );
 
							String destination = " Param Town ";
							while(destination.equals(" Param Town ")){
								System.out.println(" What would you like to do? [Shop] or [Continue] ");
								System.out.println("___________________________________________________________________________________");
								String decision = choices.next();
								if(decision.equals("Shop") || decision.equals("shop")){
									while(decision.equals("Shop") || decision.equals("shop")){
										System.out.println("Wel-came...uhhh, yu new arund ere?");
										System.out.println("Er Ding Cost 15 coins");
									while(decision.equals("Shop")|| decision.equals("shop")){
										System.out.println("   _________________________________  ");
										System.out.println("  |                                 |");
										System.out.println("  |  Option1 [Iron Sword(+10 DMG)]  |  ");
										System.out.println("  |  Option2 [Chainmail (+50HP)]    |  ");
										System.out.println("  |  Option3 [Leave]                |  ");
										System.out.println("  |_________________________________|  ");
										System.out.println("Wut're you gunna choose? [1] [2] [3]");
										String buy = choices.next();
										
										
										//Option 1
										
								if(buy.equals("1")){
									System.out.println("_________________________________________________________________________");
									System.out.println("You've obtained the Iron Sword \n[-15 coins]\n[+10 Damage]");
									System.out.println("_________________________________________________________________________");
									System.out.println("\"You dun't gut anymoor shinies, get lost\" \n Leaving...");
									Thread.sleep(4000);
									System.out.println("\"HELPPPPPP\"");
									System.out.println("-You see a girl running towards you\n\"Some slimes kidnapped the King\"");
									System.out.println("_________________________________________________________________________");
									System.out.println("Will you help rescue the King? [Yes] or [No]");
								while(buy.equals("1")){
									String answer = choices.next();
								if(answer.equals("Yes")||answer.equals("yes")){
									System.out.println("_________________________________________________________________________");
									System.out.println();
									System.out.println("... I thought kings were heavily gaurded...");
									System.out.println("The slimes are taking the King back to their laire, Hurry!");
									System.out.println();
									System.out.println("_________________________________________________________________________");
									System.out.println();
									System.out.println("Following the slime trail...");
									System.out.println();
									Thread.sleep(4000);
									System.out.println("_________________________________________________________________________");
									System.out.println("You encounter a Horned Slime [50 HP and 10 DMG");
									System.out.println();
									System.out.println("What will you do? [Fight] or [Run]");
									System.out.println();
									System.out.println("_________________________________________________________________________");
									String action1 = choices.next();
									while(buy.equals("1")){
									if(action1.equals("Fight")||action1.equals("fight")){
										System.out.println("You engaged in a fight with the Horned Slime");
										Thread.sleep(4000);
										System.out.println();
										System.out.println("_________________________________________________________________________");
										System.out.println("You sliced off a chunk of the Horned Slime[-20 DMG] ");
										System.out.println("The Horned Slime charges at you [-10HP]");
										Thread.sleep(3400);
										System.out.println("");
										System.out.println("You sliced off the horns from the slime[-20 DMG]");
										System.out.println("The Horned Slime charges at you [null]");
										System.out.println("");
										Thread.sleep(3400);
										System.out.println("The Ex-Horned Slime bursts into tiny pieces[-10 DMG]");
										System.out.println("_________________________________________________________________________");
										while(action1.equals("Fight")|| action1.equals("fight")){
											System.out.println("You encounter a Slim Slime /n What will you do? [Fight] or [Run]");
											
											
										}
									}
									else if(action1.equals("Run") || action1.equals("run")){
										System.out.println("Pussy");
									}
									else
										System.out.println("Fight or Run");
								}
								}
								// if(answer)
								}
									break;
								}
								
								
								
								
								
								//Option 2
								
								else if(buy.equals("2")){
									System.out.println("You've obtained Chainmail \n[-15 coins]\n[+50HP]");
									System.out.println("_________________________________________________________________________");
									System.out.println("You lea- \"HELPPPPPP\"");
									System.out.println("-You see a girl running towards you\n\"Some slimes kidnapped the King\"");
									System.out.println("_________________________________________________________________________");
									System.out.println("Will you help rescue the King? [Yes] or [No]");
								while(buy.equals("2")){
									String answer = choices.next();
								if(answer.equals("Yes")||answer.equals("yes")){
									System.out.println("... I thought kings were heavily gaurded...");
									System.out.println("The slimes are taking the King back to their laire, Hurry!");
								}
								}
									break;
								}
								
								
								
								
								
								//Option 3
								
								
								else if(buy.equals("3")){
									System.out.println("Wut the heckle men, geet out of er if you ain't buyin sum-inng");
									System.out.println("_________________________________________________________________________");
									System.out.println();
									System.out.println("You're leaving the shop (Please Wait)");
									Thread.sleep(5000);
									System.out.println("_________________________________________________________________________");
									System.out.println("You wal- \"HELPPPPPPPPPP\"");
									System.out.println("-You see a girl running towards you\n\"Some slimes kidnapped the King\"");
									System.out.println("_________________________________________________________________________");
									System.out.println("Will you help rescue the King? [Yes] or [No]");
								while(buy.equals("3")){
									String answer = choices.next();
								if(answer.equals("Yes")||answer.equals("yes")){
									System.out.println("... How did huge slimes even get past without the guards knowing?...");
									System.out.println("The slimes are taking the King back to their laire, Hurry!");
								}
								}
									break;
								}
								else{
									System.out.println("Dat's not no option frend");
									break;
								}
									}
									}
								}
								else if(decision.equals("Continue")||decision.equals("continue")){
									System.out.println(" Leaving town... ");
									System.out.println("HEY YOU!!! HELP!!!!");
									System.out.println("-You see a girl running towards you\n\"Some slimes kidnapped the King\"");
									System.out.println("_________________________________________________________________________");
									System.out.println("Will you help rescue the King? [Yes] or [No]");
									String answer = choices.next();
								while(decision.equals("Continue")||decision.equals("continue"));{
								if(answer.equals("Yes")||answer.equals("yes")){
									System.out.println("... I thought kings were heavily gaurded...");
									System.out.println("The slimes are taking the King back to their laire, Hurry!");
								}
								}
									break;
								}
								else{
									System.out.println("You continue to wander ...");
								
									
								}
							}

							break;
						}
						break;
					}
					else if(actions.equals("Run") || actions.equals("run")) {
						while(actions.equals("Run") || actions.equals("run")) {
							System.out.println(" You ran away from the Green Slime \n \" PUSSSYYY \"");
							System.out.println(" But the Slime charged after you, engulfing you in its stomach acid. \nThe acid was too strong, and it disintegrated you \n[GAME OVER]");
							System.out.println();
							System.out.println("Hidden Rule \"Don't be a wussy\"");
							System.out.println("Please restart game");
							System.exit(0);
							break;
						}
						break;
					}
					else {
						while(!(actions.equals("Fight")||actions.equals("fight")||actions.equals("run")||actions.equals("Run"))) {
							System.out.println("You either [Fight] or [Run]");
							System.out.println("___________________________________________________________________________________");
							System.out.println();
							break;
						}	
						break;
					}
					// break;
				}
			}






















				//Tenzin's Work
			}
			else if(direction.equals("Right")||direction.equals("right")){
				while(direction.equals("Right")||direction.equals("right")){
					System.out.println(" You walk down the Path of Calamity \nYou encounter an Anonymous Man who wields a Twig \n What will you do? [Fight] or [Chat]" );
					String actions = choices.next();
					if(actions.equals("Fight")||actions.equals("fight")) {
						while(actions.equals("Fight")||actions.equals("fight")) {
							
							String HP1 = "Inifinte" ;
							String DMG1 = " \"too much for you to handle\" " ;
							
							System.out.println("He has [ " + HP1 + " HP " + "and damgage that is " +  DMG1);
							System.out.println(" He pokes you in your butthole instantly ");
							System.out.println(" You have just been manslaughtered. Son! ");
							System.out.println(" [ Game Over ]");
							break;
						}
						break;
					}
					else if(actions.equals(" Chat ") || actions.equals(" chat ")) {
						while(actions.equals(" Chat ") || actions.equals(" chat ")) {
							System.out.println(" Howthy there! This ith the one thime of the year we're s'ppowthed tho forgeth all the bath stufth."
									+ " Stopth worryin' and bein thad abouth the thate of the wurld an for one thay, thu heck with ii. "
									+ "  ");  // https://www.youtube.com/watch?v=SCWa4Y0lmcA
						}
					}
					else {
						while(!(actions.equals(" Fight ")||actions.equals(" fight ")||actions.equals(" Chat ")||actions.equals(" chat "))) {
							System.out.println(" You either fight or chat ");
							System.out.println(" ___________________________________________________________________________________");
							System.out.println();
							break;
						}
					}
					break;
				}	
			}
			else {
				while(!(direction.equals("right")||direction.equals("Right")||direction.equals("left")||direction.equals("Left"))) {
					System.out.println("___________________________________________________________________________________");
					System.out.println("I would not go there if I were you");
					System.out.println("There are only two choices \n [Left] or [Right]");
					System.out.println("___________________________________________________________________________________");
					break;
				}
			}
		}
	}








			//William/Tenzin's Work
			else if(role.equals("Range") || role.equals("range")) {
				System.out.println("___________________________________________________________________________________");
				System.out.println("As a range, you have 100HP and 20 DMG");
				System.out.println("Here's a slingshot");
				System.out.println("~Obtain Slingshot~");
				System.out.println("___________________________________________________________________________________");
				System.out.println("~ Forest of Beginning ~");
				System.out.println("You wake up, in the middle of a field, there are 2 passages \nChoose a route [Left] or [Right]");
				String direction = choices.next();









				//William's Work
				if(direction.equals("Left")||direction.equals("left")) {
					while(direction.equals("left") || direction.equals("Left")) {
						System.out.println("You walk down the quiet trail \nYou encounter a green slime\n What will you do? [Fight] or [Run]");
						String actions = choices.next();

					}
				}












	
					//Tenzin's Work
					else if(direction.equals("Right")||direction.equals("right")){
						while(direction.equals("Right")||direction.equals("right")){
						}	
					}
					else {
						while(!(direction.equals("right")||direction.equals("Right")||direction.equals("left")||direction.equals("Left"))) {
							System.out.println("I would not go there if I were you");
							System.out.println("There's only two route \n [Left] or [Right]");
							System.out.println("___________________________________________________________________________________");
							break;
						}
	
					}
				}
				else {
					while(!(role.equals("Melee") || role.equals("melee") || role.equals("range") || role.equals("Range"))) {
						System.out.println("___________________________________________________________________________________");
						System.out.println("That's not one of the roles");
						System.out.println("Please enter one of them");
						System.out.println("[Melee] or [Range]");
						System.out.println("___________________________________________________________________________________");
						break;
					}
				}
			}
		}
		else if (begin.equals("No")||begin.equals("no")) {
			while(begin.equals("No") || begin.equals("no")) {
				System.out.println();
				System.out.println("Well you can't play the game then");
				System.out.println("Did you even read it? Here they are again");
				System.out.println();
				break;
			}
		}
		else{
			System.out.println("Huh? Bruh yes or no\n");
			System.out.println("Let's reread the rules");
				}
	
			}
		}
	
	}
	
	
