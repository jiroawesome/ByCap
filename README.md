# ByCap
- Check out examples directory for more examples.


## Installation
- `pip install ByCap`


## Example
```py
from ByCap import AnticaptchaClient, NoCaptchaTaskProxylessTask

api_key = '??'
site_key = '??'
url = 'https://www.google.com/recaptcha/api2/demo'

client = AnticaptchaClient(api_key)
task = NoCaptchaTaskProxylessTask(url, site_key)
ff = client.createTask(task)
ff.join()
print ff.get_solution_response()
```

## API Key
- Get your API Key on [anti-captcha.com](https://anti-captcha.com/).


## Note
- This library is made for python developers.
