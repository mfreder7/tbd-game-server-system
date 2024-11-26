# Fast API + Custom UDP Implementation - Game server framework

![Coverage](coverage.svg)

The goal is to build a robust and efficient solution designed to minimize latency and overhead through a custom protocol in a lean server environment. This project provides a foundational game server structure optimized for self-hosting, ensuring smooth and responsive multiplayer experiences.

## Current Functionality

- **FastAPI API**: A scalable and high-performance API built with FastAPI, handling routes for lobbies and player management.
- **Custom UDP**: Initial roughdraft.

## WIP

### Running API Locally

To execute the API locally, ensure you have the necessary dependencies installed and run:

```sh
uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
```

### Running Tests Locally

To execute the unit tests locally, ensure you have the necessary dependencies installed and run:

```sh
pytest
```

### Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your enhancements or bug fixes.

### License

As of now. None... I appreciate credit. I also appreciat tips if you find it useful: [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/L3L01PGZ3)
