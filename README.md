# ID3 Decision Tree Project

## Overview

This project involves the implementation of the ID3 (Iterative Dichotomiser 3) algorithm to create decision trees for classification tasks. The ID3 algorithm builds a decision tree by recursively partitioning the dataset based on the attribute that provides the highest information gain at each step. This project demonstrates the effectiveness of the ID3 algorithm in generating decision trees, optimizing them for accurate classification, and provides insights into its applications and limitations.
# ID3 Decision Tree Project

This project was held and tested for 4 different CSVs, of increasing difficulty, described in the assignment.

## Clone the repository

Run (within the correct directory) the following command-line (Linux):

```bash
git clone https://github.com/pmgfernandes04/ID3_Decision_Tree_Generator.git
```

## Future Work

- **Enhancements**: Finalize the 4th dataset and make a working AI based on the corresponding tree.
- **Applications**: Apply the ID3 algorithm to a broader range of datasets and problem domains.

## Results

<details><summary>Restaurant</summary>
<p>

```json
{
  "Pat": {
    "Some": "Yes",
    "Full": {
      "Hun": {
        "Yes": {
          "Type": {
            "French": "No",
            "Thai": {
              "Fri": {
                "No": "No",
                "Yes": "Yes"
              }
            },
            "Burger": "Yes",
            "Italian": "No"
          }
        },
        "No": "No"
      }
    },
    "None": "No"
  }
}
```

</p>
</details>


<details><summary>Weather</summary>
<p>

```json
{
  "Weather": {
    "sunny": {
      "Humidity": {
        "<= 77.5": "yes",
        "> 77.5": "no"
      }
    },
    "overcast": "yes",
    "rainy": {
      "Windy": {
        "False": "yes",
        "True": "no"
      }
    }
  }
}
```

</p>
</details>


<details><summary>Iris-setosa</summary>
<p>

```json
{
  "petallength": {
    "<= 2.45": "Iris-setosa",
    "> 2.45": "Not-Iris-Setosa"
  }
}
```

</p>
</details>

<details><summary>Iris-versicolor</summary>
<p>

```json
{
  "petallength": {
    "<= 2.45": "Not-Iris-versicolor",
    "> 2.45": {
      "petalwidth": {
        "<= 1.75": {
          "petallength": {
            "<= 4.95": {
              "petalwidth": {
                "<= 1.65": "Iris-versicolor",
                "> 1.65": "Not-Iris-versicolor"
              }
            },
            "> 4.95": {
              "petalwidth": {
                "<= 1.55": "Not-Iris-versicolor",
                "> 1.55": {
                  "sepallength": {
                    "<= 6.95": "Iris-versicolor",
                    "> 6.95": "Not-Iris-versicolor"
                  }
                }
              }
            }
          }
        },
        "> 1.75": {
          "petallength": {
            "<= 4.85": {
              "sepallength": {
                "<= 5.95": "Iris-versicolor",
                "> 5.95": "Not-Iris-versicolor"
              }
            },
            "> 4.85": "Not-Iris-versicolor"
          }
        }
      }
    }
  }
}
```

</p>
</details>

<details><summary>Iris-virginica</summary>
<p>

```json
{
  "petallength": {
    "<= 4.75": {
      "petalwidth": {
        "<= 1.65": "Not-Iris-virginica",
        "> 1.65": "Iris-virginica"
      }
    },
    "> 4.75": {
      "petalwidth": {
        "<= 1.75": {
          "petallength": {
            "<= 4.95": "Not-Iris-virginica",
            "> 4.95": {
              "petalwidth": {
                "<= 1.55": "Iris-virginica",
                "> 1.55": {
                  "sepallength": {
                    "<= 6.95": "Not-Iris-virginica",
                    "> 6.95": "Iris-virginica"
                  }
                }
              }
            }
          }
        },
        "> 1.75": {
          "petallength": {
            "<= 4.85": {
              "sepallength": {
                "<= 5.95": "Not-Iris-virginica",
                "> 5.95": "Iris-virginica"
              }
            },
            "> 4.85": "Iris-virginica"
          }
        }
      }
    }
  }
}
```

</p>
</details>


