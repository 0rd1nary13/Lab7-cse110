# partner: 
- James Forest & Changrong Li

# Check Your Understanding

## (1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
- Within a Github action that runs whenever code is pushed 
- Manually run them locally before pushing code
- Run them all after all development is completed
                        
- answer
- Within a GitHub action that runs whenever code is pushed
- Automated testing can detect problems immediately and prevent the merging of problematic code.



## (2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)
- answer
- no
- E2E is used to test the user behavior process and is not suitable for verifying the return values of specific functions. It is applied to unit testing.



## (3) What is the difference between navigation and snapshot mode?
- Navigation: It will evaluate the overall performance for your website. 
- Snapshot:  It’s mainly used for checking accessibility and layout issues, but it does not analyze performance of your website. 
## (4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
- Reduce Unused JavaScript and CSS: Load unused JS and CSS takes time
- Optimize Image Sizes: Can be useful if we can surnk the size of pics.
- Enable Text Compression: Can short the load time