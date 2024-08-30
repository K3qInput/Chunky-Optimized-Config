# Optimized Chunky Configuration for Minecraft 1.20.1 FFA Practice Server

This repository contains the most optimized `chunky.yml` configuration specifically tailored for a Minecraft 1.20.1 FFA practice server. The configuration is designed to minimize RAM consumption, maximize MSPT and TPS performance, and ensure stable server operations during chunk generation.

## Features

- **World Border Control**: Limits chunk generation to the necessary area, reducing resource usage.
- **Optimized Chunk Loading**: Uses fewer threads and smaller batch sizes to maintain high TPS and low MSPT.
- **Minimal World Generation**: Disables unnecessary world features like structures, oceans, and caves to save on processing power and memory.
- **Lightweight Chunk Processing**: Disables lighting generation and unloads chunks immediately after generation to free up memory.
- **Advanced Safety Settings**: Implements conservative memory and TPS thresholds to prevent server overload.
- **Reduced I/O Operations**: Disables verbose logging and automatic backups during generation to focus resources on the essential tasks.

## Usage

1. **Download the `chunky.yml`**:
   - Click the `Code` button on this repository.
   - Download the file as a `.zip`, or clone the repository using Git.

2. **Replace Your Existing `chunky.yml`**:
   - Navigate to your server directory.
   - Replace your existing `chunky.yml` with the one from this repository.
   - Ensure you back up your current `chunky.yml` before replacing it.

3. **Restart Your Server**:
   - Restart your Minecraft server to apply the changes.

## Customization

While this configuration is designed for maximum performance on an FFA practice server, you may need to tweak certain settings based on your specific server environment:

- **Threads and Batch Size**: Adjust these settings if you have more or less CPU power available.
- **Memory and TPS Thresholds**: If your server has more memory or higher TPS requirements, you might increase these thresholds.
- **World Generation Settings**: If you need specific world features, you can enable them in the configuration.

## Contributions

If you have any improvements or suggestions, feel free to fork the repository, make changes, and submit a pull request. Contributions are welcome!

## Support

For any questions or support, please open an issue on this repository, and I'll be happy to assist.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
