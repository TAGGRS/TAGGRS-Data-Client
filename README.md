# TAGGRS Data Client

The TAGGRS Data Client provides a straightforward client template for integrating webhooks with the server-side container of Google Tag Manager. Webhooks are often used to send data from third-party services, and with this client, you can seamlessly accept and process these data payloads within your GTM server-side container.

## Features

- Easy integration with Google Tag Manager server-side container.
- Accepts and processes data payloads sent via webhooks.
- Supports multiple data formats including JSON, form data, and more.
- Configurable error handling and response mechanisms.

## Prerequisites

- A Google Tag Manager account with a server-side container set up.
- Familiarity with the basics of webhooks.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/TAGGRS/TAGGRS-Data-Client.git
    ```

2. **Navigate to the GTM server-side container**: Access the Google Tag Manager dashboard, select your server-side container.

3. **Import the TAGGRS Data Client template**: Within the container, go to `Templates` > `Clients` and click on `New`. Choose to import and select the downloaded client template.

4. **Configure the template**: Fill in necessary parameters or configurations as prompted by the template.

## Usage

1. **Create a new client instance**: In your server-side container, navigate to the `Clients` section and select the TAGGRS Data Client.

2. **Configure your endpoint**: Set up the endpoint to which the webhook will send data. This can be a specific path in your server-side container URL.

3. **Test your setup**: Send a sample webhook request to your configured endpoint to ensure data is accepted and processed correctly.

## Troubleshooting

- Ensure your GTM server-side container is properly set up and accessible.
- Double-check the endpoint configuration.
- Examine the logs within the GTM server-side container for any issues related to data processing.

## Contributing

Contributions are welcome! Please create a pull request or open an issue on GitHub.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Support

For questions or assistance, please open an issue on our GitHub repository.
