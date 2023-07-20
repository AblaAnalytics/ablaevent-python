# Setup Python

Follow the instructions below to send custom events from your Python backend.

## Install

````
pip install ablaevent

````
## Configure
````
from ablaevent import Posthog

posthog = Posthog(project_api_key='phc_ySCF4YinUf6DxprJ5B0jXtzgijeTqFkWPsIIfC3yTrC', host='https://e.abla.io')

````
            
## Send an Event

````
posthog.capture('test-id', 'test-event')

````
