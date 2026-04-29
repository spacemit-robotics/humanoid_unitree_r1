cmake_minimum_required(VERSION 3.16)
project(humanoid_unitree_r1)

install(PROGRAMS
    scripts/run_driver_r1.sh
    scripts/run_control_r1.sh
    scripts/run_hmi_r1.sh
    scripts/run_sim2sim_r1.sh
    scripts/download_models_r1.sh
    DESTINATION bin
)
