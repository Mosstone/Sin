    Pulls images from the trusted namespace in dockerhub, runs a security scan, and builds it
    using singularity with optimal settings for mutable .sif containers, along with a command
    tree allowing for standardized shell and execution
    
    For remote execution for NAT access, memorizes the default address and credentials to use
    simplifying access from edge devices that only need a single default
    
    TODO:
        Refactor to go, facilitate imports with dynamic switching
        Refine remote execution, multimodal connection profiles
        Keep sandboxes in .enclave folders
        Add proc to create hard coded wrapper/container pairs
        Wireguard integration for remote
        Test cuda access from sandboxes
        Create normal users within container
        Add system to manage packages externally
        Add rsync/syncthing directory shared with host
        Make singularity portable, possibly create fork with erlang embedded
    
    Buerer, D. (2025). sin [Computer software]. 10.5281/zenodo.15593249
