# Calendar application with companion application
> Just out of time is a calendar application for use with a low refresh screen. Controls are provided through a companion app, since most low refresh screens have no built in user controls.

The application is built as a demo application for data gathering tools such as open-telemetry integrations, mixpanel or other user tracking tools and more. But next to these demo qualities, the application is meant to be used.


## Calendar Application
### Targeted devices
- Raspberry Pi with connected screen (or other IOT devices)

## Companion Application
### Targeted devices
The companion application is a web application, though features might be specific to the device used. The following devices will be first in mind during development
- Phones or handheld devices
- Laptops or devices with larger screens.

### Features
#### Calendar application
- Visualize calendar tasks
- Realtime feedback to companion app changes.
- Session or device identification across sessions

#### Companion application
- update calendar view
- connect calendars
- add, update and delete tasks

### Technical features
- Opentelemetry
    - traces
    - metrics
    - logs
- Mixpanel
    - events
        - connected companion devices
        - custom events
    - user properties 
        - device dimensions
