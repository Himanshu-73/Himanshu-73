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

### 🧰 Languages and Tools


<img align="left" alt="Git" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
<img align="left" alt="Linux" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" />
<img align="left" alt="HTML" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-plain.svg" />
<img align="left" alt="CSS" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-plain.svg" />
<img align="left" alt="JavaScript" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg" />
<img align="left" alt="React" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" />
<img align="left" alt="NodeJS" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" />
<img align="left" alt="Python" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-plain.svg" />
<img align="left" alt="C++" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-line.svg" />
<img align="left" alt="GitHub" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" />
<img align="left" alt="Bash" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" />
<br />

#

<h3 align="left">💌 Connect with me:</h3>
<p align="center">
<a href="https://www.linkedin.com/in/himanshu-sahu-b65136276?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="okayniraj" height="30" width="40" /></a>
<a href="https://www.instagram.com/savvy.himanshu?igsh=MTZ0d3cyb3ppeHNtNQ==" target="_blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="okay.niraj" height="30" width="40" /></a>
<a href="" target="_blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/codeforces.svg" alt="xyz" height="30" width="40" /></a>
<a href="" target="_blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="xyz" height="30" width="40" /></a>
<a href="" target="_blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/topcoder.svg" alt="xyz" height="30" width="40" /></a>
   <a href="" target="_blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hashnode.svg" alt="xyz" height="30" width="40" /></a>
<a
</p>

