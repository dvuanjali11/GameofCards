import java.util.*;
public class CardGame {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        HashSet<String> uniqueSymbols= new HashSet<>();
        HashSet<String> uniquecards= new HashSet<>();
        System.out.println("Enter the number of cards: ");
        int n= scanner.nextInt();
        scanner.nextLine();
        for(int i=0; i<n; i++){
            System.out.println("Enter a card: ");
            String card= scanner.nextLine();
            String[] cardParts= card.split(" ");
            if(!uniqueSymbols.contains(cardParts[0])){
                uniqueSymbols.add(cardParts[0]);
                uniquecards.add(card);
            }
            
        }
        System.out.println("Cards in set are: ");
        TreeSet<String>sortedCards= new TreeSet<>(uniquecards);
        for(String card: sortedCards){
            System.out.println(card);
        }
        scanner.close();
    }
}
