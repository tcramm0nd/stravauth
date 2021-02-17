# stravauth
Simple authentication for Strava Apps

## Installation
Clone directly from repo:
`git clone https://github.com/tcramm0nd/stravauth.git`

## Examples
```python
from stravauth import Client
# Initializes a Strava API Client and writes a credentials
# file to the working directory
client = Client()
```
```python
from stravauth import Client
# Initializes a Strava API Client and sets the directory where 
# credentials are read/written.
client = Client(credentials_path='custom/directory/')
```