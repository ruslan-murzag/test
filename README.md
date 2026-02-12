Traceback (most recent call last):
  File "C:\Users\00062700\PycharmProjects\Ivanti\venv\lib\site-packages\selenium\webdriver\common\driver_finder.py", line 67, in _binary_paths
    output = SeleniumManager().binary_paths(self._to_args())
  File "C:\Users\00062700\PycharmProjects\Ivanti\venv\lib\site-packages\selenium\webdriver\common\selenium_manager.py", line 55, in binary_paths
    return self._run(args)
  File "C:\Users\00062700\PycharmProjects\Ivanti\venv\lib\site-packages\selenium\webdriver\common\selenium_manager.py", line 129, in _run
    raise WebDriverException(
selenium.common.exceptions.WebDriverException: Message: Unsuccessful command executed: C:\Users\00062700\PycharmProjects\Ivanti\venv\lib\site-packages\selenium\webdriver\common\windows\selenium-manager.exe --browser MicrosoftEdge --language-binding python --output json; code: 65
{'code': 65, 'message': 'error sending request for url (https://msedgedriver.azureedge.net/LATEST_RELEASE_144_WINDOWS)', 'driver_path': '', 'browser_path': ''}



The above exception was the direct cause of the following exception:

Traceback (most recent call last):
  File "C:\Users\00062700\PycharmProjects\Ivanti\main.py", line 10, in <module>
    driver = webdriver.Edge(options=edge_options)
  File "C:\Users\00062700\PycharmProjects\Ivanti\venv\lib\site-packages\selenium\webdriver\edge\webdriver.py", line 45, in __init__
    super().__init__(
  File "C:\Users\00062700\PycharmProjects\Ivanti\venv\lib\site-packages\selenium\webdriver\chromium\webdriver.py", line 50, in __init__
    if finder.get_browser_path():
  File "C:\Users\00062700\PycharmProjects\Ivanti\venv\lib\site-packages\selenium\webdriver\common\driver_finder.py", line 47, in get_browser_path
    return self._binary_paths()["browser_path"]
  File "C:\Users\00062700\PycharmProjects\Ivanti\venv\lib\site-packages\selenium\webdriver\common\driver_finder.py", line 78, in _binary_paths
    raise NoSuchDriverException(msg) from err
selenium.common.exceptions.NoSuchDriverException: Message: Unable to obtain driver for MicrosoftEdge; For documentation on this error, please visit: https://www.selenium.dev/documentation/webdriver/troubleshooting/errors/driver_location


Process finished with exit code 1
