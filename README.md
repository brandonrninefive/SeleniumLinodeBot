# Selenium Linode Bot
This is a simple Python bot which uses Selenium to navigate the website [http://www.linode.com/](http://www.linode.com/)  and purchase servers. Users can configure how many servers they want to order, as well as the credentials associated with their Linode account by editing the included checkout.conf JSON file. The script is configured to use the PhantomJS headless webdriver, which is included as a NodeJS dependency. Chromedriver is also included as a dependency in the case that you don't want to use a headless webdriver.
