cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "src/SparkFun_LIS331.cpp"
                    INCLUDE_DIRS "src/."
                    REQUIRES "arduino"
                    )

project(SparkFun_LIS331)
