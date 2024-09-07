<p align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=200&size=35&pause=1000&color=00E1F7&center=true&random=false&width=650&lines=%E2%98%85+Install+Package+Files;%5BSwift%5D+iOS+App%2FTweak+Developer;%5BAutoHotKey%5D+Windows+Developer" alt="Typing SVG" /></a>
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=200&size=25&duration=10000&pause=500&color=DED2FF&center=true&random=false&width=650&lines=Passion+for+Coding+%3C3" alt="Typing SVG" /></a>
</p>

<p align= "center">
  <img height= "150" src="https://github-readme-stats.vercel.app/api?username=pkgFiles&theme=merko&show_icons=true&include_all_commits=false" />
  <img height= "150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=pkgFiles&theme=merko&layout=compact" />
</p>

```golang
import Foundation

protocol Bio {
    
    func getUserInformation() -> [String: Any]
}

class GitHub: Bio {

    static var shared = GitHub()
    
    func loadBio() {
        let userInformations: [String: Any] = getUserInformation()
        print(userInformations)
    }
    
    func getUserInformation() -> [String: Any] {
        return [
            "🙎🏼‍♂️": "[25/y] ♂︎",
            "📍": "Germany",
            "📝": "Developing iOS Apps/Tweaks and small Windows Tools"
        ]
    }
}

GitHub.shared.loadBio()

```
