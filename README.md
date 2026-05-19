# Lab7 Unit Testing and E2E Testing

Jason Wang

## Check Your Understanding
1. Where would you fit your automated tests in your Recipe project development pipeline? 

I would fit my automated tests within a Github Action that runs whenever code is pushed as it can automatically detect any errors within the change that breaks existing and new changes

2. Would you use an end to end test to check if a function is returning the correct input?

No

3. What is the difference between navigation and snapshot mode?

Navigation mode analyzes the page when loaded; whereas snapshot mode analyzes a particular state of the page.

4. Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

    - We could set the `lang` attribute as there is currently none. This might cause the screen reader to mismatch the content of the page.
    - Add meta descriptions to summarize page content
    - store product images to a json file instead of grabbing from the web as those images are unreliable over time