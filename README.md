Для работы нужно скачать ardupilot_gazebo по гайду;
Далее нужно прописать пути в bashrc

export GZ_SIM_SYSTEM_PLUGIN_PATH=$HOME/gz_ws/src/ardupilot_gazebo/build:${GZ_SIM_SYSTEM_PLUGIN_PATH}
export GZ_SIM_RESOURCE_PATH=$HOME/gz_ws/src/agro_drone_gz_sim/worlds:$HOME/gz_ws/src/agro_drone_gz_sim/models:${GZ_SIM_RESOURCE_PATH}
Эти две строчки нужны обязательно!!!

Вместо gz_ws пишите ВАШЕ название воркспейса
