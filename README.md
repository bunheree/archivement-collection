# 🏆 Achievement Collection

> Elevate Your Profile!

Welcome to the Achievement Collection library, a dynamic set of components designed to enhance your portfolio website by seamlessly integrating badges and certificates.

Whether you're showcasing your professional accomplishments, educational milestones, or any noteworthy achievements, this library provides the perfect solution to make your profile stand out.

## How to Get Started

### Installation

```bash
npm install achievement-collection
```

or

```bash
yarn add @achievement-collection
```

### Usage

#### Example ReactJS

```jsx
import GGBadgets from '@archivement-collection'
...
<GGBadgets className='gg-wrapper' limit={5}/>
```

View Demo: [CodeSandBox](https://codesandbox.io/p/sandbox/achievement-collection-34wq7k?file=%2Fsrc%2FApp.js%3A11%2C1)

#### Github Readme profile

```md
[![Google Developer Profile badges](https://github-readme-activity-graph.vercel.app/graph?username=loanngo99&theme=merko)](https://github.com/ashutosh00710/github-readme-activity-graph)
```

### Documentation

1. List components

    * GGBadgets
    * MicrosoftMedal
    * CourseraCert

2. Common properties

    Param          |Type  |Value                  |Description
    ---------------|------|-----------------------|----------------------------------------------------
    `className`    |string|                       | Class name of parent class wrapper
    `itemClassName`|string|                       | Class name of each item
    `limit`        |number|                       | Limit the badget can view
    `viewStyle`    |string| `card` `icon` `title` | How to display badges. Default viewStyle is `card`

3. Special properties

    Component      |Param     |Type  |Value                   |Description
    ---------------|----------|------|------------------------|-------------------------------------
    MicrosoftMedal |`type`    |string|`both` `badget` `trophy`| Display Type. Default type is `both`

## Community Collaboration

I believe in the power of collaboration! If you encounter any issues, have suggestions for improvement, or simply want to share your thoughts, please open an issue [here](https://github.com/loanngo99/archivement-collection/issues) or reach out to us directly. Let's work together to create an even more impressive and user-friendly library for showcasing achievements.

Thank you for choosing the Achievement Collection library. Let your accomplishments shine on your portfolio website and leave a lasting impression on visitors. 🚀

## License

[MIT License](https://github.com/loanngo99/archivement-collection/blob/main/LICENSE). Copyright (c) 2024 Emma Ngo
