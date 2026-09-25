# REST API

This directory will contain the REST API for FlightRisk AI.

The API will:

- Receive flight information from users or other applications
- Validate incoming input
- Apply the same preprocessing used during model training
- Submit the processed data to the selected production model
- Return the predicted disruption risk as JSON
- Return explanation or confidence information where appropriate

Planned implementation:
- FastAPI
- Input validation with Pydantic
- Automated API tests
