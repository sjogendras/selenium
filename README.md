# selenium

1. Create a console project
2. Install selenium web driver from nuget package
3. using OpenQA.Selenium;
   using OpenQA.Selenium.Firefox;
   
   IWebDriver driver = new FirefoxDriver();
	 driver.Url = "http://www.google.com";
   
4. If drivers not found then can be downloaded from - https://github.com/mozilla/geckodriver/releases
5. using OpenQA.Selenium.Chrome;
   IWebDriver driver = new ChromeDriver();
	driver.Url = "http://www.google.com";
   
