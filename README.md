# ID3 Decision Tree Project

## Overview

This project involves the implementation of the ID3 (Iterative Dichotomiser 3) algorithm to create decision trees for classification tasks. The ID3 algorithm builds a decision tree by recursively partitioning the dataset based on the attribute that provides the highest information gain at each step. This project demonstrates the effectiveness of the ID3 algorithm in generating decision trees, optimizing them for accurate classification, and provides insights into its applications and limitations.

This project was held and tested for 4 different csvs, of increasing dificulty, described in the assignment.

## Clone the repository:

Run (within the correct directory) the following command-line (linux):

    ```bash
    git clone [https://github.com/yourusername/id3-decision-tree-project.git](https://github.com/pmgfernandes04/ID3_Decision_Tree_Generator.git)
    ```
## Future Work

- **Enhancements**: Finalize the 4th dataset and make a working AI based on the corresponding tree.
- **Applications**: Apply the ID3 algorithm to a broader range of datasets and problem domains.

## Results

<details><summary>tree</summary>
<p>
    
{
      'Pat': {
            'Some': 'Yes',
            'Full': {
                  'Hun': {
                        'Yes': {
                              'Type': {
                                    'French': 'No',
                                    'Thai': {
                                          'Fri': {
                                                'No': 'No',
                                                'Yes': 'Yes'
                                          }
                                    },
                                    'Burger': 'Yes',
                                    'Italian': 'No'
                              }
                        },
                        'No': 'No'
                  }
            },
            'None': 'No'
      }
}
<p>
</details>
