# Micro-service whose role is to serve configuration data for other micro-services.

application.yml : Common configuration (all applications / all profiles).
Application-specific configuration files have names based on each application's spring.application.name property.
Profile-specific configuration files can be named with a suffix equal to the name of the active profile.


