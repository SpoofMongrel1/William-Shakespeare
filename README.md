# William-Shakespeare
An essay about William Shakespeare
In java script

public class EssayAboutShakespeare {

    public static void main(String[] args) {
        // Creating an instance of the EssayAboutShakespeare class
        EssayAboutShakespeare essay = new EssayAboutShakespeare();

        // Calling methods to print each section of the essay
        essay.printIntroduction();
        essay.printBiography();
        essay.printLiteraryContributions();
        essay.printFamousWorks();
        essay.printLegacy();
    }

    // Method to print the introduction
    public void printIntroduction() {
        System.out.println("Essay about William Shakespeare");
        System.out.println("-------------------------------");
        System.out.println("William Shakespeare, often regarded as the greatest playwright and poet in the English language,...");
        System.out.println();
    }

    // Method to print the biography section
    public void printBiography() {
        System.out.println("Biography");
        System.out.println("-------------------------------");
        System.out.println("William Shakespeare was born in Stratford-upon-Avon, England, in 1564...");
        System.out.println();
    }

    // Method to print the section about Shakespeare's literary contributions
    public void printLiteraryContributions() {
        System.out.println("Literary Contributions");
        System.out.println("-------------------------------");
        System.out.println("Shakespeare's works spanned various genres including tragedy, comedy, and history...");
        System.out.println();
    }

    // Method to print the section about Shakespeare's famous works
    public void printFamousWorks() {
        System.out.println("Famous Works");
        System.out.println("-------------------------------");
        System.out.println("Some of Shakespeare's most renowned plays include Hamlet, Romeo and Juliet, Macbeth, Othello, and King Lear...");
        System.out.println();
    }

    // Method to print the section about Shakespeare's legacy
    public void printLegacy() {
        System.out.println("Legacy");
        System.out.println("-------------------------------");
        System.out.println("Shakespeare's works continue to be studied, performed, and adapted across the globe...");
        System.out.println("His influence on literature, language, and culture is immeasurable...");
        System.out.println();
    }
}
