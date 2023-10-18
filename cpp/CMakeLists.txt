cmake_minimum_required (VERSION 2.8.12)

project (StepupApiGwApp LANGUAGES CXX)

SET (stepup_gw_app_sources 
    ${stepup_gw_app_sources}
    src/StepUpGwApp.cpp
     )
        
add_executable(ApiGw ${stepup_gw_app_sources})


  
