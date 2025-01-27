# Newton-Raphson x Extended Euclidean Algorithm

<img align="right" width="100px" src="./.media/math.png">

![Version Badge](https://img.shields.io/badge/status-in%20development-red)

This repository contains the implementations presented in the study article `Cryptography: Newton-Raphson and Extended Euclid, A Comparative Study`. The study aims to evaluate the effectiveness of the Extended Euclidean Algorithm (EEA) compared to the Newton-Raphson (NR) method. To achieve this, benchmarks were performed using a (highly) simplified RSA implementation as a pratical example. The article was developed as the final project for the Numerical Calculus course at UTFPR-TD.

## Development status

<!---
Possible status:
:white_check_mark: Done
:black_square_button: In progress
:white_square_button: Planned
--->

| Feature                  | Status                             | Description |
|:-------------------------|:-----------------------------------|:------------|
| Software designing       | :black_square_button: In progress  | Decide which languages to use and how to implement the RSA, EEA and NR algorithms |
| Simplified RSA           | :white_square_button: Planned      | Implement the 5 steps of RSA, except for the 'd' parameter (calculated using EEA or NR) |
| Extended Euclidean (EEA) | :white_square_button: Planned      | Implement the Extended Euclidean Algorithm |
| Newton-Raphson (NR)      | :white_square_button: Planned      | Implement the Newton-Raphson method |

## Instructions

To compile the code and run the benchmarks, use the `build.sh` script:

```bash
$ ./build.sh
```

## License

This project is licensed under the [MIT License](https://opensource.org/license/MIT). Fell free to use, modify, and distribute the code as needed. See the [LICENSE](LICENSE) file for more information.
