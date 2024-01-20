public class HTMLGenerator {
    public static void main(String[] args) {
        // Using StringBuilder to build the HTML content
        StringBuilder htmlBuilder = new StringBuilder();

        // Step 1: Doctype, Head, and Body Elements
        htmlBuilder.append("  My Web Page\n");

        // Step 2: Semantic Tags (h1, main)
        htmlBuilder.append(" Welcome to My Web Page!!!!");
        htmlBuilder.append("This website will show you the top expensive cars in the world.")
        // Step 3: List with at Least Three Items

        htmlBuilder.append("    Web Development</li>\n");
        htmlBuilder.append("    Photography\n");
        htmlBuilder.append("    Travel</li>\n");
       

        // Step 4: At Least Three Images
       
        htmlBuilder.append("                <img src=\"https://www.boxymo.ie/news/img/koenigsegg-trevita.jpg\ \n");

       
        htmlBuilder.append("                <img src=\"https://www.boxymo.ie/news/img/lamborghini.jpg\n");
        
        htmlBuilder.append("                <img src=\"https://www.boxymo.ie/news/img/lykan-hypersport.jpg\n");
        

        // Step 5: Link to an External Source
        htmlBuilder.append("\n Click the link for more information:");
        
        htmlBuilder.append("<li><a href=\"https://www.boxymo.ie/news/most-expensive-cars-in-the-world.aspx\" \n");
       
       

        // Closing HTML tags
        htmlBuilder.append("Thank you for join my websites!!!!");
        

        // Print the generated HTML
        System.out.println(htmlBuilder.toString());
    }
}
