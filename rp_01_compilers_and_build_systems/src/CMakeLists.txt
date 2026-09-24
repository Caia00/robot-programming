add_library(core_library SHARED
    utils/property_eigen.cpp
    utils/blob.cpp
    utils/id_context.cpp
    utils/serializer.cpp
    utils/deserializer.cpp
    utils/identifiable.cpp
    utils/id_placeholder.cpp
    utils/object_data.cpp
    utils/property_container.cpp
    utils/property_container_manager.cpp
    utils/property.cpp
    utils/property_identifiable.cpp
    utils/serializable.cpp
    utils/serialization_context.cpp
    messages/base_sensor_message.cpp
    messages/odometry_message.cpp
    messages/pose_message.cpp
    data_structures/matrix.hpp

)


target_include_directories(core_library PUBLIC .)


target_link_libraries(core_library Eigen3::Eigen)  
