# fleet

automatic setup of several of my mini copmputers 

## Initial setup of raspberry pi host

    ansible-playbook initial-setup-rpi.yaml --extra-vars "host=rpi-jinx" --ask-pass
