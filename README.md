# hostickstatus

------------------EXAMPLE BANNER--------------------
{
  "banner": {
    "active": true,
    "type": "incident",
    "title": "We're experiencing issues",
    "message": "Our team is investigating. Sorry for the inconvenience."
  }
}

---------TYPES OF BANNERS-------------------------
types of banner:
BannerType = "maintenance" | "incident" | "warning" | "info"

===============EXAMPLE JSON=============================
--------------MAINTENANCE BANNER-------------------------
{
  "banner": {
    "active": true,
    "type": "maintenance",
    "title": "Scheduled Maintenance",
    "message": "We’ll be performing scheduled maintenance. Some features may be temporarily unavailable."
  }
}
-------------------INCIDENT BANNER----------------------------------------------
{
  "banner": {
    "active": true,
    "type": "incident",
    "title": "Service Disruption",
    "message": "We are currently experiencing an issue affecting some services. Our team is actively working to resolve it."
  }
}
----------------WARNING BANNER--------------------------------------------
{
  "banner": {
    "active": true,
    "type": "warning",
    "title": "Temporary Notice",
    "message": "Some features may not work as expected. Please proceed with caution while we address this."
  }
}
---------------INFO BANNER ------------------------------------------
{
  "banner": {
    "active": true,
    "type": "info",
    "title": "Update",
    "message": "We’ve made some updates to improve your experience. Check out what’s new!"
  }
}

----------------------------------------------------------------------
