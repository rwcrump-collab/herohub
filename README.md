# HeroHub

A simple Flask web application for displaying a gallery of heroes. HeroHub provides a clean and easy way to showcase your favorite heroes with images and descriptions.

## Features

- 🦸 Display a gallery of heroes with images
- 🖼️ Simple and clean web interface
- 🚀 Built with Flask for easy deployment
- 📝 Easy to add new heroes

## Project Structure

```
herohub/
├── app/
│   ├── main.py              # Main Flask application
│   └── templates/
│       └── gallery.html     # Gallery template
├── images/                  # Hero images directory
├── docs/
│   └── gallery.md          # Gallery documentation
├── requirements.txt        # Python dependencies
├── CONTRIBUTING.md         # Contribution guidelines
└── SECURITY.md            # Security policy
```

## Installation

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

### Setup

1. Clone the repository:
```bash
git clone https://github.com/Jason-M-Richards/herohub.git
cd herohub
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

### Running the Application

1. Start the Flask development server:
```bash
python app/main.py
```

2. Open your web browser and navigate to:
```
http://localhost:5000
```

### Adding a New Hero

1. Add your hero's image to the `images/` folder (e.g., `wolverine.jpg`)

2. Open `app/main.py` and add an entry to the `gallery` list:
```python
{"name": "Wolverine", "species": "Mutant", "image": "wolverine.jpg"}
```

3. Restart the application to see your new hero!

## Dependencies

- Flask >= 2.0.0
- Werkzeug >= 2.0.0

## Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to:
- Fork the repository
- Create a feature branch
- Submit a pull request
- Follow our coding standards

## Security

Security is important to us. If you discover a security vulnerability, please see our [SECURITY.md](SECURITY.md) for information on how to report it responsibly.

## Documentation

For more detailed information about using the gallery feature, see [docs/gallery.md](docs/gallery.md).

## License

This project is open source. Please check the repository for license information.

## Questions or Issues?

- Open an [Issue](https://github.com/Jason-M-Richards/herohub/issues) for bug reports or feature requests
- Start a [Discussion](https://github.com/Jason-M-Richards/herohub/discussions) for questions

---

Built with ❤️ using Flask
