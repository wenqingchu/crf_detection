## Compile:

    mkdir build
    cd build
    cmake -D CMAKE_BUILD_TYPE=Release ..
    make
    cd ..


## Usage:

    build/examples/dense_inference proposal_scores likelihood output scene_score object_weight global_weight


## Function:

    adjust the initial scores for proposals with object-level and image-level context information
