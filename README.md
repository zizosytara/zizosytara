<div align="center">

<!-- 3D Animated C++ Header -->
<a href="https://github.com/ziadriyad">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=30&duration=4000&pause=1000&color=20C20E&background=0D111700&center=true&vCenter=true&width=800&height=100&lines=console.log(%22Hello%2C%20World!%22);System.out.println(%22I'm%20Ziad%20Riyad%22);std::cout<<%22C%2B%2B%20Developer%22;print(%22From%20Egypt%20🇪🇬%22)" alt="Typing Animation" />
</a>

<!-- Matrix-style C++ animation -->
<img src="https://raw.githubusercontent.com/ziadriyad/ziadriyad/main/assets/matrix.gif" width="600"/>

<!-- Animated Tech Stack -->
<div>
  <img src="https://skillicons.dev/icons?i=cpp,c,py,linux,git,vscode,cmake&perline=7" />
</div>

</div>

## 🚀 C++ Expertise

```cpp
// Professional Skills Matrix
#include <skills.h>

enum class SkillLevel { Expert, Advanced, Intermediate };

template<typename T>
class SkillMatrix {
    vector<pair<string, SkillLevel>> skills;
public:
    SkillMatrix() {
        skills.emplace_back("Modern C++ (20/23)", SkillLevel::Expert);
        skills.emplace_back("STL & Data Structures", SkillLevel::Expert);
        skills.emplace_back("Multi-threading", SkillLevel::Advanced);
        skills.emplace_back("Template Metaprogramming", SkillLevel::Advanced);
        skills.emplace_back("Performance Optimization", SkillLevel::Expert);
        skills.emplace_back("Competitive Programming", SkillLevel::Advanced);
    }
    
    void display() const {
        for(const auto& [skill, level] : skills) {
            cout << "🧠 " << skill << " | ";
            switch(level) {
                case SkillLevel::Expert: cout << "★★★★★"; break;
                case SkillLevel::Advanced: cout << "★★★★☆"; break;
                case SkillLevel::Intermediate: cout << "★★★☆☆"; break;
            }
            cout << endl;
        }
    }
};
