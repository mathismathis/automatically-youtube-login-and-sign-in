# automatically-youtube-login-and-sign-in
from selenium import webdriver
a=webdriver.Firefox()
a.get("http://www.youtube.com/")
a.find_element_by_xpath("//input[@id='search']").send_keys("random technologies")
a.find_element_by_xpath("//button[@id='search-icon-legacy']").click()
a.quit()
