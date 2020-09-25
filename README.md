# Power Platform Actions Example Usage
![Manual or API export and commit CUCore](https://github.com/paulbreuler/powerplatform-devops-example/workflows/Manual%20or%20API%20export%20and%20commit%20CUCore/badge.svg?branch=main)

![Deploy CUCore to modular dev environments](https://github.com/paulbreuler/powerplatform-devops-example/workflows/Deploy%20CUCore%20to%20modular%20dev%20environments/badge.svg)

## Dispatch export from a custom event

**Example**
```
POST /repos/paulbreuler/powerplatform-actions-example/dispatches HTTP/1.1
Host: api.github.com
Authorization: Bearer <token>
Content-Type: application/json

{
    "event_type": "export"
}
```
