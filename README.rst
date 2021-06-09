########################
home-assitant-blueprints
########################
Collection of self-made/modified blueprints

=============
Apply locally
=============

..  code-block::

    TARGET_HOST='Hello world'
    TARGET_PATH='Hello path'
    rsync --delete --exclude .git --exclude .vscode -avc ./ ${TARGET_HOST}:${TARGET_PATH} 
    