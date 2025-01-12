# Frequently Asked Questions

??? info "Where can I get support?"
    Please [email us](mailto:support@web3labs.com) with your query and a member of our team will come back to you promptly.

??? info "Is it possible to customise Epirus?"
    Yes, its possible to customise numerous parts of Epirus, including the logos, colors and currency that users see. Please [email us](mailto:support@web3labs.com) for more information.
    
??? info "Are you hiring?"
    Please head to our [jobs portal](https://web3labs.workable.com/) for current listings.

??? warning "Unable to create instance on Azure - the template deployment is not valid"
    ![Azure creation error](img/azure_create_error.png)
    ```
    The template deployment 'blk-technologies.azure-blockchain-explorer-templa-20190701100047' is not valid according to the validation procedure. The tracking id is '494a6331-33c6-4c13-8871-359117dfa70b'. See inner errors for details. Please see https://aka.ms/arm-deploy for usage details.
    ```

	Check that the instance name that you have used is globally unique. Using a common name such as `test` in the below example will fail:

	![Epirus instance name](img/epirus_instance_name.png)

	If this does not resolve your issue, please [email us](mailto:hi@web3labs.com) with details of the parameters you're trying to use.

??? warning "I'm trying to upload a contract metadata file but it's failing"
    Please refer to the [Contract Registry](metadata.md) documentation.
