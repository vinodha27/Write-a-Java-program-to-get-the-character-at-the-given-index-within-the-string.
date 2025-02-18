# Write-a-Java-program-to-get-the-character-at-the-given-index-within-the-string.

class Main {
    public static void main(String[] args) {
        String a="javaprogram";
        char b='p';
        for(int i=0;i<a.length();i++)
        {
            if((a.charAt(i))==b)
            System.out.println(i);
        }
    }
}
