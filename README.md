# MalDetect

MalDetect is a deep-learning malware detection system built using the [EMBER dataset](https://www.tensorflow.org) of 1.1 million executables. This neural network was trained on over 600,000 [Portable Executable](https://docs.microsoft.com/en-us/windows/win32/debug/pe-format) samples and achieved an accuracy of 97.8% in detecting a file as malicious.

## Features Engineering

<p align="center">
  <img src="https://i.imgur.com/RiVOPoE.jpg" alt="Image by Ange Albertini"/>
</p>

Features include a handpicked selection of 100 PE libraries, boolean file properties (has_imports, has_exports, has_tls, etc.), 64 bytes of the PE entry point (used as a signature), and other features relevant to malware detection.

## License

This project is released under the MIT license. Source code provided by [EMBER](https://github.com/endgameinc/ember) is covered by the GNU Affero General Public License version 3 (AGPL-v3). The data files provided by [EMBER](https://github.com/endgameinc/ember) are covered by the MIT License.
