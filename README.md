## Hey I'm Himanshu!

[![Typing SVG](https://readme-typing-svg.demolab.com/?lines=Full+Stack+Developer;Tech+Explorer+Open-Source+Enthusiast+and+Lifelong+Learner;Code,+Coffee+and+Curiosity.)](https://git.io/typing-svg)

##  Profile Highlights 

```cpp
#include <iostream>
#include <string>
#include <vector>
#include <unordered_map>
#include <cstdlib>  //  random greetings
#include <ctime>    // seeding random generator

class Himanshu {
private:
    const std::string username = "Himanshu-73";
    const std::string name = "Himanshu";
    const std::string web = "https://HimanshuSahu.onrender.com";
    const std::unordered_map<std::string, std::vector<std::string>> code = {
        {"frontend", {"HTML", "CSS", "JavaScript", "React", "Bootstrap"}},
        {"backend", {"Python", "Flask", "Node.js", "Express", "C++"}},
        {"database", {"MongoDB", "MySQL"}},
        {"devops", {"Docker", "GitHub Actions", "AWS"}},
        {"tools", {"GIT", "GitHub", "Pandas", "VSCode"}},
        {"misc", {"Firebase", "GNU/Linux"}}
    };
    const std::vector<std::string> architecture = {"SPA", "Serverless"};

    std::vector<std::string> greetings = {"Hello, world!", "Hey there!", "Greetings, traveler!", "Welcome to my bio!"};

public:
    std::string toString() const {
        std::string bio = "Name: " + name + "\n"
                          + "Username: " + username + "\n"
                          + "Website: " + web + "\n"
                          + "Skills:\n";

        for (const auto& stack : code) {
            bio += "- " + stack.first + ": ";
            for (const auto& tech : stack.second) {
                bio += tech + ", ";
            }
            bio.pop_back();  // Remove last comma
            bio.pop_back();
            bio += "\n";
        }

        bio += "Architectural Knowledge: ";
        for (const auto& arch : architecture) {
            bio += arch + ", ";
        }
        bio.pop_back();  // Remove last comma
        bio.pop_back();
        return bio;
    }

    // greeting method
    void say_hi() const {
        std::srand(std::time(nullptr));  
        int random_index = std::rand() % greetings.size();
        std::cout << greetings[random_index] << std::endl;
    }
};

int main() {
    Himanshu me;
    me.say_hi();
    std::cout << me.toString() << std::endl;
    return 0;
}


```

