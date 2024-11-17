
# Lab VM Migration Report

## Challenges Encountered
- **Resource Constraints**: One of the main challenges was running out of disk space and RAM on my laptop. This caused the lab to stop and fail multiple times. I had to repeat the entire lab three times before it worked because of these limitations.
- **Mobility Service Installation**: At first, I installed the Azure Migrate Mobility service on the wrong VM by mistake. This led to delays and more troubleshooting until I figured out the issue and reinstalled it on the correct VM.
- **Appliance Registration Issues**: Registering the migration appliance with Azure Migrate was difficult. I had to double-check my network configurations and access permissions to make sure everything was set up properly.
- **Failed Azure VM Creation**: I tried to create a VM directly in Azure to use as a migration source, but it didn't work. This happened due to configuration errors, like incorrect network settings and mismatched resource specifications.
- **Configuration Server Setup**: I initially set up the configuration server incorrectly, which required me to reset it and go through the setup again following Azure’s documentation.
- **Restarting the Migration VM**: At one point, I restarted the VM I was migrating, which caused the entire migration process to fail and forced me to start over.
- **Incorrect Version of Mobility Agent**: I also discovered that I had used an outdated version of the Azure Mobility agent, which led to compatibility issues and needed to be updated before continuing.

## Resolution Strategies
- **Freeing Up Resources**: I made more disk space available and adjusted the RAM allocation on my laptop to improve the performance of VMware Workstation and reduce interruptions.
- **Reinstalling the Mobility Service**: I ensured that I reinstalled the mobility service on the correct VM which is source Vm, which resolved that specific issue.
- **Double-Checking Registration Steps**: I carefully reviewed the steps for appliance registration and checked the network settings to ensure they were accurate, which fixed the registration problems.
- **Correcting the Configuration Server**: I followed Azure Migrate’s documentation closely to set up the configuration server correctly after resetting it.
- **Updating the Mobility Agent**: I downloaded and installed the correct, updated version of the Azure Mobility agent, which solved the compatibility issues.

## Challenges and Insights
- **Resource Management**: The limited resources on my local machine (disk space and RAM) were a big challenge. This taught me that having a more powerful local setup or using cloud-based resources would make migrations much smoother.
- **Service Installation and Registration**: Installing and registering services properly is essential. Any mistakes, like using the wrong version or restarting at the wrong time, can cause serious delays or failures.
- **Role of the Configuration Server**: I learned how important the configuration server is for Azure Migrate. Any misconfiguration can disrupt the migration process, so careful planning and double-checking are key.
- **VM Restart Impact**: Restarting the migration VM without proper preparation can cause the entire process to stop and fail, highlighting the need for caution during migration activities.

## Key Takeaways
- **Attention to Detail**: The migration process is complex and requires careful attention to details, especially during service installation and setup.
- **Pre-Migration Preparation**: Proper assessments, having enough local resources, and using the correct software versions are essential for a smooth migration.
- **Troubleshooting Skills**: This experience gave me valuable hands-on practice in solving issues related to VM assessments, appliance setup, and Azure migrations.
- **Learning from Challenges**: I gained practical knowledge about how to recover from migration failures and the importance of not restarting or changing things mid-process unless it's planned and needed.

