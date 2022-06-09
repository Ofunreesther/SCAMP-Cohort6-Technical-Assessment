# Javascript Technical Assessment  

- Fork the [javascript track assessment](https://github.com/she-code-africa/javascript-ta).
- Clone the repository to your local computer.
- Add your solution to the specificied position.
- Commit your solution.
- Push your update to your repository.
- Submit your repository URL on the provided google form.
- NOTE: make sure to follow the instruction on the readme.md/README.md

- Using Javascript, write a function that checks if a number is a Prime number or not and returns True/False.

Note: A prime number(or a prime) is a positive integer that is only divisible by 1 and itself. For example, 2, 3, 5, 7, 11 are the first few prime numbers.

## Submission: 

- Push your solution to the github repo created

- submit the URL on the application form here: [Cohort 6 Application](http://shecodeafrica.org/events) 







*Good luck!*


















function isPrime(num) {
    if (num < 2)
       return false
    else if (num === 2) {
        return true
    }
    else {
        for(let i = 2; i < num ; i++) {
            if(num % i === 0) {
                return false
            }
        }
        return true
    } 
}