# tributary3
Backend Infrastructure for Ford's Sensor Streaming System 

This codebase powers a Flask server that seamlessly records and manages data from embedded vehicle sensors. It features two key endpoints:\
/record: This endpoint is called periodically by the vehicle's sensors to post real-time data to a Redis database.
/collect: User-facing mobile applications use this endpoint to retrieve the latest sensor data for a smooth and responsive user experience
