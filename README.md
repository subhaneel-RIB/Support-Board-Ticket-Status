**Support Board Dashboard**

     This project uses Chart.js to display the status of support tickets in a visual format. The dashboard represents various ticket statuses through bar charts, making it easy to track the progress and current status of each ticket.

**Instructions for Updating the Chart**

  Edit the Data:

    Navigate to the datasets section of the chart configuration.
    
    Modify the data array for each dataset to reflect the updated counts.
    
    Example: For "Closed", update the numbers to reflect the current closed tickets.

**Example format:**

    datasets: [
      {
        label: "Closed",
        backgroundColor: "#003366",
        data: [updated_count_1, updated_count_2]
      },
      {
        label: "In QA",
        backgroundColor: "#4B4B4B",
        data: [updated_count_3, updated_count_4]
      }
    ]
    
**Commit the Changes:**

    After updating the data, commit your changes to the repository.

**Deploy:**

    Wait for the deployment to complete, which typically takes around 2-5 minutes.
    
    Once deployed, you will be able to see the updated chart reflecting your changes.

**Notes**
Ensure the data you enter matches the ticket statuses for accurate reporting.

For additional datasets or customizations, refer to the Chart.js documentation.
