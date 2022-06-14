# ByCap
- Check out examples directory for more examples.

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


## Note
- This library is made for python developers.
