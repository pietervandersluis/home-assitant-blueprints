########################
home-assitant-blueprints
########################
Collection of self-made/modified blueprints

=============
Apply locally
=============

..  code-block::

    rsync --delete --exclude .git --exclude .vscode -avc ./ kubernetes-node:/opt/kubernetes_host_path/ha-v2/config/blueprints/automation/pietervandersluis/ 