servicenow
==========

snowbound.py is a python based script which creates tickets from the events that are found for a specified query.

It uses snowbound.cfg to capture Boundary and ServiceNow URLs, credentials and settings.

The script will create a ticket from event data and designate a short description, priority and place the event message, severity and id in the work notes of the ticket along with a deep link to the Boundary event.
