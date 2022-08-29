Furst gym library was installed by cloning the source code repository and then installing the library using the commands :


git clone https://github.com/openai/gym && cd gym


sudo apt install python3-pip 
#it was required to install the pip command


pip install -e


Then pygame was installed since it was required to simulate the cartpole using the command:
pip install gym[classic_control]

Then, the initial kp, kd, ki values were tuned experimentally and a simple PID controller was implemented as explained in the shared link.
