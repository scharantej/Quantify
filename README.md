## Flask Application Design for Prototyping Assistance

### HTML Files

- **index.html:**
  - Main page of the application.
  - Contains a form for creating new experiments and a table to display existing experiments.

- **create_experiment.html:**
  - Form for creating a new experiment.
  - Includes fields for experiment name, description, custom metrics, and success criteria.

- **experiment_detail.html:**
  - Page for displaying the details of a specific experiment.
  - Shows the experiment's information, metrics, and success criteria.

- **collect_results.html:**
  - Interface for collecting and submitting experiment results.
  - Allows users to input the measured values for each custom metric.

- **results_analysis.html:**
  - Page for displaying the collected results and analyzing them.
  - Provides graphs and statistics to help users identify optimal design solutions.

### Routes

- **index:**
  - Displays the homepage (`index.html`).

- **create_experiment:**
  - Handles the creation of new experiments.
  - Validates the input data and stores the experiment details in a database.

- **experiment_detail:**
  - Shows the details of a specific experiment.
  - Allows users to edit the experiment's information and metrics.

- **collect_results:**
  - Processes the submitted experiment results.
  - Stores the results in a database for further analysis.

- **results_analysis:**
  - Generates graphs and statistics based on the collected results.
  - Helps identify trends, patterns, and potential design improvements.

- **delete_experiment:**
  - Deletes an experiment from the database.

### Database

- The application utilizes a database to store the following data:
  - Experiment details (name, description, metrics, success criteria)
  - Collected experiment results