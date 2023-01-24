# Command JUJU
```
actions                      List actions defined for an application.
add-cloud                    Adds a cloud definition to Juju.
add-credential               Adds a credential for a cloud to a local client and uploads it to a controller.
add-k8s                      Adds a k8s endpoint and credential to Juju.
add-machine                  Provision a new machine or assign one to the model.
add-model                    Adds a hosted model.
add-relation                 Relate two applications.
add-space                    Add a new network space.
add-ssh-key                  Adds a public SSH key to a model.
add-storage                  Adds storage to a unit after it has been deployed.
add-unit                     Adds one or more units to a deployed application.
add-user                     Adds a Juju user to a controller.
agree                        Agree to terms.
agreements                   List user's agreements.
attach                       Alias for 'attach-resource'.
attach-resource              Update a resource for an application.
attach-storage               Attaches existing storage to a unit.
autoload-credentials         Attempts to automatically detect and add credentials for a cloud.
bind                         Change bindings for a deployed application.
bootstrap                    Initializes a cloud environment.
budget                       Update a budget.
cached-images                Shows cached os images.
cancel-action                Cancel pending or running actions.
cancel-task                  Alias for 'cancel-action'.
change-user-password         Changes the password for the current or specified Juju user.
charm-resources              Display the resources for a charm in a repository.
clouds                       Lists all clouds available to Juju.
collect-metrics              Collect metrics on the given unit/application.
config                       Gets, sets, or resets configuration for a deployed application.
consume                      Add a remote offer to the model.
controller-config            Displays or sets configuration settings for a controller.
controllers                  Lists all controllers.
create-backup                Create a backup.
create-storage-pool          Create or define a storage pool.
create-wallet                Create a new wallet.
credentials                  Lists Juju credentials for a cloud.
dashboard                    Print the Juju Dashboard URL, or open the Juju Dashboard in the default browser.
debug-code                   Launch a tmux session to debug hooks and/or actions.
debug-hook                   Alias for 'debug-hooks'.
debug-hooks                  Launch a tmux session to debug hooks and/or actions.
debug-log                    Displays log messages for a model.
default-credential           Sets local default credentials for a cloud on this client.
default-region               Sets the default region for a cloud.
deploy                       Deploys a new application or bundle.
destroy-controller           Destroys a controller.
destroy-model                Terminate all machines/containers and resources for a non-controller model.
detach-storage               Detaches storage from units.
diff-bundle                  Compare a bundle with a model and report any differences.
disable-command              Disable commands for the model.
disable-user                 Disables a Juju user.
disabled-commands            List disabled commands.
download                     Locates and then downloads a CharmHub charm.
download-backup              Download a backup archive file.
enable-command               Enable commands that had been previously disabled.
enable-destroy-controller    Enable destroy-controller by removing disabled commands in the controller.
enable-ha                    Ensure that sufficient controllers exist to provide redundancy.
enable-user                  Re-enables a previously disabled Juju user.
exec                         Run the commands on the remote targets specified.
export-bundle                Exports the current model configuration as a reusable bundle.
expose                       Makes an application publicly available over the network.
find                         Queries the CharmHub store for available charms or bundles.
find-offers                  Find offered application endpoints.
firewall-rules               Alias for 'list-firewall-rules'.
get-constraints              Displays machine constraints for an application.
get-model-constraints        Displays machine constraints for a model.
grant                        Grants access level to a Juju user for a model, controller, or application offer.
grant-cloud                  Grants access level to a Juju user for a cloud.
gui                          Alias for 'dashboard'.
help                         Show help on a command or other topic.
help-tool                    Alias for 'hook-tool'.
hook-tool                    Show help on a Juju charm hook tool.
hook-tools                   Alias for 'hook-tool'.
import-filesystem            Imports a filesystem into the model.
import-ssh-key               Adds a public SSH key from a trusted identity source to a model.
info                         Displays detailed information about CharmHub charms.
kill-controller              Forcibly terminate all machines and other associated resources for a Juju controller.
list-actions                 Alias for 'actions'.
list-agreements              Alias for 'agreements'.
list-cached-images           Alias for 'cached-images'.
list-charm-resources         Alias for 'charm-resources'.
list-clouds                  Alias for 'clouds'.
list-controllers             Alias for 'controllers'.
list-credentials             Alias for 'credentials'.
list-disabled-commands       Alias for 'disabled-commands'.
list-firewall-rules          Prints the firewall rules.
list-machines                Alias for 'machines'.
list-models                  Alias for 'models'.
list-offers                  Alias for 'offers'.
list-payloads                Alias for 'payloads'.
list-plans                   Alias for 'plans'.
list-regions                 Alias for 'regions'.
list-resources               Alias for 'resources'.
list-spaces                  Alias for 'spaces'.
list-ssh-keys                Alias for 'ssh-keys'.
list-storage                 Alias for 'storage'.
list-storage-pools           Alias for 'storage-pools'.
list-subnets                 Alias for 'subnets'.
list-users                   Alias for 'users'.
list-wallets                 Alias for 'wallets'.
login                        Logs a user in to a controller.
logout                       Logs a Juju user out of a controller.
machines                     Lists machines in a model.
metrics                      Retrieve metrics collected by specified entities.
migrate                      Migrate a hosted model to another controller.
model-config                 Displays or sets configuration values on a model.
model-default                Alias for 'model-defaults'.
model-defaults               Displays or sets default configuration settings for new models.
models                       Lists models a user can access on a controller.
move-to-space                Update a network space's CIDR.
offer                        Offer application endpoints for use in other models.
offers                       Lists shared endpoints.
payloads                     Display status information about known payloads.
plans                        List plans.
refresh                      Refresh an application's charm.
regions                      Lists regions for a given cloud.
register                     Registers a controller.
relate                       Alias for 'add-relation'.
reload-spaces                Reloads spaces and subnets from substrate.
remove-application           Remove applications from the model.
remove-cached-images         Remove cached OS images.
remove-cloud                 Removes a cloud from Juju.
remove-consumed-application  Alias for 'remove-saas'.
remove-credential            Removes Juju credentials for a cloud.
remove-k8s                   Removes a k8s cloud from Juju.
remove-machine               Removes one or more machines from a model.
remove-offer                 Removes one or more offers specified by their URL.
remove-relation              Removes an existing relation between two applications.
remove-saas                  Remove consumed applications (SAAS) from the model.
remove-space                 Remove a network space.
remove-ssh-key               Removes a public SSH key (or keys) from a model.
remove-storage               Removes storage from the model.
remove-storage-pool          Remove an existing storage pool.
remove-unit                  Remove application units from the model.
remove-user                  Deletes a Juju user from a controller.
rename-space                 Rename a network space.
resolve                      Alias for 'resolved'.
resolved                     Marks unit errors resolved and re-executes failed hooks.
resources                    Show the resources for an application or unit.
resume-relation              Resumes a suspended relation to an application offer.
retry-provisioning           Retries provisioning for failed machines.
revoke                       Revokes access from a Juju user for a model, controller, or application offer.
revoke-cloud                 Revokes access from a Juju user for a cloud.
run                          Run the commands on the remote targets specified.
run-action                   Queue an action for execution.
scale-application            Set the desired number of application units.
scp                          Securely transfer files within a model.
set-application-base         Alias for 'set-series'.
set-constraints              Sets machine constraints for an application.
set-credential               Relates a remote credential to a model.
set-default-credential       Alias for 'default-credential'.
set-default-region           Alias for 'default-region'.
set-firewall-rule            Sets a firewall rule.
set-meter-status             Sets the meter status on an application or unit.
set-model-constraints        Sets machine constraints on a model.
set-plan                     Set the plan for an application.
set-series                   Set an application's series.
set-wallet                   Set the wallet limit.
show-action                  Shows detailed information about an action.
show-action-output           Show results of an action.
show-action-status           Show results of all actions filtered by optional ID prefix.
show-application             Displays information about an application.
show-cloud                   Shows detailed information for a cloud.
show-controller              Shows detailed information of a controller.
show-credential              Shows credential information stored either on this client or on a controller.
show-credentials             Alias for 'show-credential'.
show-machine                 Show a machine's status.
show-model                   Shows information about the current or specified model.
show-offer                   Shows extended information about the offered application.
show-space                   Shows information about the network space.
show-status                  Report the status of the model, its machines, applications and units.
show-status-log              Output past statuses for the specified entity.
show-storage                 Shows storage instance information.
show-unit                    Displays information about a unit.
show-user                    Show information about a user.
show-wallet                  Show details about a wallet.
sla                          Set the SLA level for a model.
spaces                       List known spaces, including associated subnets.
ssh                          Initiates an SSH session or executes a command on a Juju machine or container.
ssh-keys                     Lists the currently known SSH keys for the current (or specified) model.
status                       Alias for 'show-status'.
storage                      Lists storage details.
storage-pools                List storage pools.
subnets                      List subnets known to Juju.
suspend-relation             Suspends a relation to an application offer.
switch                       Selects or identifies the current controller and model.
sync-agent-binary            Copy agent binaries from the official agent store into a local controller.
sync-tools                   Alias for 'sync-agent-binary'.
trust                        Sets the trust status of a deployed application to true.
unexpose                     Removes public availability over the network for an application.
unregister                   Unregisters a Juju controller.
update-cloud                 Updates cloud information available to Juju.
update-credential            Updates a controller credential for a cloud.
update-credentials           Alias for 'update-credential'.
update-k8s                   Updates an existing k8s endpoint used by Juju.
update-public-clouds         Updates public cloud information available to Juju.
update-storage-pool          Update storage pool attributes.
upgrade-charm                Alias for 'refresh'.
upgrade-controller           Upgrades Juju on a controller.
upgrade-dashboard            Upgrade to a new Juju Dashboard version.
upgrade-gui                  Alias for 'upgrade-dashboard'.
upgrade-juju                 Alias for 'upgrade-model'.
upgrade-machine              Alias for 'upgrade-series'.
upgrade-model                Upgrades Juju on all machines in a model.
upgrade-series               Upgrade the Ubuntu series of a machine.
users                        Lists Juju users allowed to connect to a controller or model.
version                      Print the Juju CLI client version.
wallets                      List wallets.
whoami                       Print current login details.
```
