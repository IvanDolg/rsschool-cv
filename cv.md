# Ivan Dauhalaptseu 
## Java Backend Developer 
***
![Ivan](/rsschool-cv/photo.png)

***

## Contact iformation:
#### Phone: +375445514458
#### E-mail: ivandolgolaptev@gmail.com
#### Telegram: [@GIOVANNI_DOL](https://t.me/GIOVANNI_DOL)
#### LinkedIn: [Ivan Dolgolaptseu](https://www.linkedin.com/in/ivan-dolgolaptseu-231b08232/)
#### Github: [Ссылка на  Github](https://github.com/IvanDolg)
#### Discord: Ivan Dauhalaptseu (@IvanDolg)
***

## About Myself:
I am currently a second-year student at the Belarusian State University of Informatics and Radioelectronics, studying in the Faculty of Information Technology and Management, with a major in Automated Information Processing Systems.

I'm curious individual who is always eager to learn and take on new challenges.

Currently, I'm studying Java EE technology and JavaScript, while also working on improving my English skills.

***

## Skills and Proficiency:
* MySql, MySql Workbench
* SqlServer 
* Java Core, Intellij IDEA 
* C++, Visual Studio 
* Git, Github 
* VS Code
* Adobe Photoshop

***

## Education:
* 2nd year student at the Belarusian State University of Informatics and Radioelectronics, Faculty of Information Technology and Management, specialisation Automated Information Processing Systems
* EPAM Training center «Introduction to Java»  

***


## Junior Developer:

 * The book 'Clean Code' by Robert Martin 
 * The book "The Perfect Programmer" by Robert Martin
 * The book "Java Programming for Beginners" by A.N. Vasiliev
 
***

## Code Example

 
```

 class Binomical{
    private int [] binoms;
    Binomical (int n){
        binoms = new int[n+1];
        binoms[0] = 1;
        for (int k=1; k<=n; k++){
            binoms[k] = binoms [k-1]*(n-k+1)/k;
        }
    }
    public String toString(){
        String txt = "|";
        for (int k=0; k<binoms.length; k++){
            txt += binoms[k] + "|";
        }
        return txt;
    }
}

public class Main {
    public static void main(String[] args) {
        Binomical A = new Binomical(5);
        Binomical B = new Binomical(10);
        System.out.println(A);
        System.out.println(B);
    }
}

 ```

***

## Languages:
* Russian - Native
* Belarusian - Native
* English -  Intermedia