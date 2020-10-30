# Hello 👋, I'm Xavier Briole

```javascript
class AboutMe extends React.Component {
  constructor(props) {
    super(props);

    this.state = {
      languages: [],
      tools: [],
      devOps: [],
      methods: [],
    };
  }

  handleLanguages() {
    this.setState({
      languages: ["javascript", "typescript", "php", "html", "scss"],
    });
  }

  handleTools() {
    this.setState({
      tools: ["flow", "redux", "reactjs", "react-native", "jest"],
    });
  }

  handleDevOps() {
    this.setState({
      devOps: ["github-actions", "docker"],
    });
  }

  handleMethods() {
    this.setState({
      methods: ["scrum", "tdd"],
    });
  }

  render() {
    return null;
  }
}
```

## Statistics 📊

![xavierbriole's github stats](https://github-readme-stats.vercel.app/api?username=xavierbriole&show_icons=true&hide=stars)
[![xavierbriole's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=xavierbriole)](https://github.com/anuraghazra/github-readme-stats)
