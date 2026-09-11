# Temirlan Sapargali

## Contacts
* Email: krutoytemirlan2007@gmail.com
* Telegram: @Fernoel

## Short info
I want to become competent front-end developer who's able to utilize technologies like three.js, GSAP, and react to realize my own design ideas.

## Skills
* React
* Golang
* JavaScript
* Java
* OpenTelemetry
* Git
* Three.js
* GSAP

## Code example
```java
package problems;

import java.util.Scanner;

public class Problem9 {
    public static void start() {
        Scanner sc = new Scanner(System.in); // Initializing Scanner to read user input
        // Base parameters
        System.out.println("Enter the binomial coefficients n and k");
        int n = sc.nextInt();
        int k = sc.nextInt();

        double startTime = System.nanoTime();
        System.out.println(binomialCoefficient(n, k));
        double endTime = System.nanoTime();
        System.out.println("Time taken: " + ((endTime - startTime) / 1000000) + " milliseconds");
    }


    /**
     * Returns binomial coefficient at specified <b>n</b> and <b>k</b>. <br>
     * Runs in O(2<sup>n</sup>) complexity.
     * @param n Specified parameter.
     * @param k Specified parameter.
     * @return Binomial coefficient at specified parameters.
     */
    public static int binomialCoefficient(int n, int k) {
        if (k < 0 || n < 0) {
            throw new IllegalArgumentException("Negative binomial coefficient parameters");
        }

        if (k == 0 || k == n) {
            return 1;
        }

        return binomialCoefficient(n - 1, k - 1) + binomialCoefficient(n - 1, k);
    }
}
```

## Experience
* [threedaitumap](https://github.com/fernoe1/threedaitumap) (React, js, three.js) 3D interior map of my campus that I'm currently working on.

## Education
* Astana IT University

## English 
* B2