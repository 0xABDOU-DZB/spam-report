# spam-report

from selenium.webdriver.chrome.webdriver import WebDriver

PATH = "chromedriver****"
driver: WebDriver = webdriver.Chrome (PATH)
driver.get ("https://instagram.com")
sleep (3)
driver.find_element_by_xpath ("//input[@name=\"username\"]") \
    .send_keys ('password')
driver.find_element_by_xpath ("//input[@name=\"password\"]") \
    .send_keys ('@name')
driver.find_element_by_xpath ("//button[@type=\"submit\"]") \
    .click()
sleep(3)
driver.find_element_by_xpath ("//button[contains(text(),  'Plus tard')]") \
    .click()
driver.find_element_by_xpath ("//button[contains(text(),  'Plus tard')]") \
    .click()
sleep(3)
driver.get("https://www.instagram.com/*****")
sleep(3)
driver.find_element_by_xpath("/html/body/div[1]/section/main/div/header/section/div[1]/div/button")\
               .click()
sleep(3)
driver.find_element_by_xpath("/html/body/div[5]/div/div/div/div/button[3]")\
               .click()
sleep(3)
driver.find_element_by_xpath("/html/body/div[5]/div/div/div/div[2]/div/div/div/div[3]/button[2]")\
    .click()
sleep(3)
driver.find_element_by_xpath("/html/body/div[5]/div/div/div/div[2]/div/div/div/div[3]/button[1]")\
    .click()
sleep(3)
driver.find_element_by_xpath("/html/body/div[5]/div/div/div/div[2]/div/div/div/div[3]/button[1]")\
    .click()
sleep(2)
driver.find_element_by_xpath("/html/body/div[5]/div/div/div/div/div/div/div[2]/button")\
   .click(2)
sleep(2)   
driver.find_element_by_xpath("/html/body/div[5]/div/div/div/div[2]/div/div/div/div[3]/button[1]")\
    .click(3)
sleep(2)    
driver.find_element_by_xpath("/html/body/div[5]/div/div/div/div[2]/div/div/div/div[3]/button[1]")\
    .click(2)
sleep(3)
