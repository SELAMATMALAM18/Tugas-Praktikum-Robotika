.
├── build
│   ├── COLCON_IGNORE
│   └── lab_comm
│       ├── colcon_build.rc
│       ├── colcon_command_prefix_setup_py.sh
│       ├── colcon_command_prefix_setup_py.sh.env
│       ├── lab_comm -> /ws/src/lab_comm/lab_comm
│       ├── lab_comm.egg-info
│       │   ├── PKG-INFO
│       │   ├── SOURCES.txt
│       │   ├── dependency_links.txt
│       │   ├── entry_points.txt
│       │   ├── requires.txt
│       │   ├── top_level.txt
│       │   └── zip-safe
│       ├── launch
│       │   └── lab_comm.launch.py -> /ws/src/lab_comm/launch/lab_comm.launch.py
│       ├── package.xml -> /ws/src/lab_comm/package.xml
│       ├── prefix_override
│       │   ├── __pycache__
│       │   │   └── sitecustomize.cpython-310.pyc
│       │   └── sitecustomize.py
│       ├── resource
│       │   └── lab_comm -> /ws/src/lab_comm/resource/lab_comm
│       ├── setup.cfg -> /ws/src/lab_comm/setup.cfg
│       ├── setup.py -> /ws/src/lab_comm/setup.py
│       └── share
│           └── lab_comm
│               └── hook
│                   ├── pythonpath_develop.dsv
│                   ├── pythonpath_develop.ps1
│                   └── pythonpath_develop.sh
├── config
├── data
├── install
│   ├── COLCON_IGNORE
│   ├── _local_setup_util_ps1.py
│   ├── _local_setup_util_sh.py
│   ├── lab_comm
│   │   ├── lib
│   │   │   ├── lab_comm
│   │   │   │   ├── motion_action_server
│   │   │   │   ├── processing_node
│   │   │   │   ├── reset_service
│   │   │   │   └── sensor_publisher
│   │   │   └── python3.10
│   │   │       └── site-packages
│   │   │           └── lab-comm.egg-link
│   │   └── share
│   │       ├── ament_index
│   │       │   └── resource_index
│   │       │       └── packages
│   │       │           └── lab_comm -> /ws/build/lab_comm/resource/lab_comm
│   │       ├── colcon-core
│   │       │   └── packages
│   │       │       └── lab_comm
│   │       └── lab_comm
│   │           ├── hook
│   │           │   ├── ament_prefix_path.dsv
│   │           │   ├── ament_prefix_path.ps1
│   │           │   ├── ament_prefix_path.sh
│   │           │   ├── pythonpath.dsv
│   │           │   ├── pythonpath.ps1
│   │           │   └── pythonpath.sh
│   │           ├── launch
│   │           │   ├── __pycache__
│   │           │   │   └── lab_comm.launch.cpython-310.pyc
│   │           │   └── lab_comm.launch.py -> /ws/build/lab_comm/launch/lab_comm.launch.py
│   │           ├── package.bash
│   │           ├── package.dsv
│   │           ├── package.ps1
│   │           ├── package.sh
│   │           ├── package.xml -> /ws/build/lab_comm/package.xml
│   │           └── package.zsh
│   ├── local_setup.bash
│   ├── local_setup.ps1
│   ├── local_setup.sh
│   ├── local_setup.zsh
│   ├── setup.bash
│   ├── setup.ps1
│   ├── setup.sh
│   └── setup.zsh
├── launch
├── log
│   ├── COLCON_IGNORE
│   ├── build_2026-09-08_07-33-43
│   │   └── logger_all.log
│   ├── build_2026-09-08_07-36-22
│   │   ├── events.log
│   │   └── logger_all.log
│   ├── build_2026-09-08_07-36-37
│   │   ├── events.log
│   │   └── logger_all.log
│   ├── build_2026-09-13_13-00-36
│   │   ├── events.log
│   │   ├── lab_comm
│   │   │   ├── command.log
│   │   │   ├── stderr.log
│   │   │   ├── stdout.log
│   │   │   ├── stdout_stderr.log
│   │   │   └── streams.log
│   │   └── logger_all.log
│   ├── build_2026-09-13_13-01-23
│   │   ├── events.log
│   │   ├── lab_comm
│   │   │   ├── command.log
│   │   │   ├── stderr.log
│   │   │   ├── stdout.log
│   │   │   ├── stdout_stderr.log
│   │   │   └── streams.log
│   │   └── logger_all.log
│   ├── build_2026-09-13_13-02-21
│   │   ├── events.log
│   │   ├── lab_comm
│   │   │   ├── command.log
│   │   │   ├── stderr.log
│   │   │   ├── stdout.log
│   │   │   ├── stdout_stderr.log
│   │   │   └── streams.log
│   │   └── logger_all.log
│   ├── latest -> latest_build
│   └── latest_build -> build_2026-09-13_13-02-21
└── src
    └── lab_comm
        ├── lab_comm
        │   ├── __init__.py
        │   ├── __pycache__
        │   │   ├── __init__.cpython-310.pyc
        │   │   ├── motion_action_server.cpython-310.pyc
        │   │   ├── processing_node.cpython-310.pyc
        │   │   ├── reset_service.cpython-310.pyc
        │   │   └── sensor_publisher.cpython-310.pyc
        │   ├── motion_action_server.py
        │   ├── processing_node.py
        │   ├── reset_service.py
        │   └── sensor_publisher.py
        ├── launch
        │   └── lab_comm.launch.py
        ├── package.xml
        ├── resource
        │   └── lab_comm
        ├── setup.cfg
        ├── setup.py
        └── test
            ├── test_copyright.py
            ├── test_flake8.py
            └── test_pep257.py
