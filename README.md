# Power Platform Actions Example Usage

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
