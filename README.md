# saconvert - Simplified Unit Conversion Library

saconvert is a Python library that simplifies unit conversions across various measurement systems. It currently supports length conversions and provides an intuitive interface for developers to perform conversions effortlessly.

## Installation

You can install saconvert using pip:

```bash
pip install saconvert
```

## Supported Conversions

saconvert currently supports the following length conversions:

- Meter
- Kilometer
- Centimeter
- Millimeter
- Micrometer
- Nanometer
- Mile
- Yard
- Foot
- Inch
- Light Year

## Usage

To use saconvert in your Python project, follow these simple steps:

```python
# Import LengthConverter, the only thing supported in the saconvert module (for now)
from saconvert.conversions import LengthConverter

# Perform a length conversion (converts Nanometer to Light Year (for all the different conversions, scroll up!))
converter = LengthConverter(20, "Nanometer")
print(converter.to_light_year())
```

## Contributing

We welcome contributions to enhance saconvert's functionality and add support for more conversions. To contribute, please follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name for your feature.
3. Make your changes and commit them with a clear message.
4. Push your changes to your forked repository.
5. Submit a pull request to the main repository.

## License

saconvert is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

Start simplifying your unit conversions with saconvert today! Reach new levels of productivity and make your codebase cleaner and more efficient. Happy coding!
