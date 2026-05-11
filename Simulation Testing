# Experiment 1: Online Banking Testing (ParaBank)
# Test Cases:
# 1. Login with valid credentials
# 2. Login with invalid credentials
# 3. Fund transfer
# 4. View transaction history
# 5. Logout

from selenium import webdriver
from selenium.webdriver.common.by import By
import time

driver = webdriver.Chrome()
driver.get("https://parabank.parasoft.com")

# Test Case 1: Valid Login
driver.find_element(By.NAME, "username").send_keys("john")
driver.find_element(By.NAME, "password").send_keys("demo")
driver.find_element(By.XPATH, "//input[@value='Log In']").click()
time.sleep(3)

# Test Case 2: Transfer Funds
driver.find_element(By.LINK_TEXT, "Transfer Funds").click()
driver.find_element(By.ID, "amount").send_keys("100")
driver.find_element(By.XPATH, "//input[@value='Transfer']").click()
time.sleep(3)

# Test Case 3: Logout
driver.find_element(By.LINK_TEXT, "Log Out").click()

driver.quit()


# Experiment 2: Standardized Testing Framework
# Test Cases:
# 1. Product search
# 2. Add to cart
# 3. Login validation
# 4. UI validation
# 5. Error handling

from selenium import webdriver
from selenium.webdriver.common.by import By
import time

driver = webdriver.Chrome()
driver.get("https://practicesoftwaretesting.com")

# Test Case 1: Search Product
search = driver.find_element(By.CSS_SELECTOR, "input[type='search']")
search.send_keys("Hammer")
time.sleep(2)

# Test Case 2: Click Product
driver.find_element(By.XPATH, "//img").click()
time.sleep(2)

# Test Case 3: Add to Cart
driver.find_element(By.XPATH, "//button[contains(text(),'Add to cart')]").click()
time.sleep(3)

driver.quit()

# Experiment 3: Agile & DevOps Testing (SauceDemo)
# Test Cases:
# 1. Login
# 2. Add to cart
# 3. Remove item
# 4. Checkout
# 5. Logout

from selenium import webdriver
from selenium.webdriver.common.by import By
import time

driver = webdriver.Chrome()
driver.get("https://www.saucedemo.com")

# Test Case 1: Login
driver.find_element(By.ID, "user-name").send_keys("standard_user")
driver.find_element(By.ID, "password").send_keys("secret_sauce")
driver.find_element(By.ID, "login-button").click()
time.sleep(2)

# Test Case 2: Add to Cart
driver.find_element(By.XPATH, "//button[text()='Add to cart']").click()
time.sleep(2)

# Test Case 3: Go to Cart
driver.find_element(By.CLASS_NAME, "shopping_cart_link").click()
time.sleep(2)

driver.quit()


# Experiment 4: Shift-Left Testing (Herokuapp)
# Test Cases:
# 1. Login authentication
# 2. Dropdown selection
# 3. File upload
# 4. Broken links
# 5. Dynamic content

from selenium import webdriver
from selenium.webdriver.common.by import By
import time

driver = webdriver.Chrome()
driver.get("https://the-internet.herokuapp.com/login")

# Test Case 1: Login
driver.find_element(By.ID, "username").send_keys("tomsmith")
driver.find_element(By.ID, "password").send_keys("SuperSecretPassword!")
driver.find_element(By.CSS_SELECTOR, "button").click()
time.sleep(3)

# Test Case 2: Verify Success Message
success = driver.find_element(By.ID, "flash").text
print("Login Message:", success)

driver.quit()


# Experiment 5: KPI-Based Testing (Automation Exercise)
# Test Cases:
# 1. User registration
# 2. Login
# 3. Product search
# 4. Add to cart
# 5. Checkout

from selenium import webdriver
from selenium.webdriver.common.by import By
import time

driver = webdriver.Chrome()
driver.get("https://automationexercise.com")

# Test Case 1: Click Signup/Login
driver.find_element(By.LINK_TEXT, "Signup / Login").click()
time.sleep(2)

# Test Case 2: Enter Email
driver.find_element(By.NAME, "email").send_keys("test@example.com")
driver.find_element(By.NAME, "password").send_keys("123456")
driver.find_element(By.XPATH, "//button[text()='Login']").click()
time.sleep(3)

# Test Case 3: Search Product
driver.find_element(By.NAME, "search").send_keys("Dress")
driver.find_element(By.ID, "submit_search").click()
time.sleep(3)

driver.quit()
