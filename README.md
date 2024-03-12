```cpp
class Bio : public Profile {
public:
    std::string name = "Jack Pike";
    std::string email = "jackvernonpike@gmail.com";
};

class Skills : public Profile {
public:
    std::vector<std::string> languages        = {"Python", "C++", "Javascript", "Bash", "Objective C"};
    std::vector<std::string> frontend         = {"Next.js", "Alpine.js"};
    std::vector<std::string> backend          = {"Node", "Express", "Flask"};
    std::vector<std::string> desktop          = {"DirectX", "DearIMGUI"};
    std::vector<std::string> databases        = {"MySQL", "MongoDB"};
    std::vector<std::string> devOps           = {"Git", "GitHub Actions"};
    std::vector<std::string> toolchains       = {"npm", "bun"};
    std::vector<std::string> hosting          = {"Oracle Cloud", "Cloudflare", "Digital Ocean"};
    std::vector<std::string> operatingSystems = {"GNU/Linux", "Windows"};
    std::vector<std::string> iot              = {"Raspberry Pi", "Amazon Alexa"};
    std::vector<std::string> editors          = {"Visual Studio Code"};
};
```
