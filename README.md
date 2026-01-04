<img align="right" src="https://komarev.com/ghpvc/?username=niclqs&label=Profile%20views&color=green&style=flat">
<hr>

```ts
export default class Attributes {
  /**
   * Returns languages spoken and the user's age.
   * @returns A tuple containing an array of languages and the user's age.
   */
  static life(): [string[], number] {
    const languages = ['German', 'English', 'Russian'];
    const age = 22;
    return [languages, age];
  }

  /**
   * Returns coding skills, specializations, and development tools.
   * @returns A tuple containing skill levels, specializations, and development environment tools.
   */
  static coding(): [{ expert: string[]; intermediate: string[]; learning: string[] }, string[], string[]] {
    const skillLevels = {
      expert: ['TypeScript', 'Java', 'Lua 5.4'],
      intermediate: ['PHP', 'C#'],
      learning: ['C++']
    };
    const specializations = ['Fullstack', 'AI', 'Automation'];
    const tools = ['Cursor', 'Postman', 'PostgreSQL'];
    return [skillLevels, specializations, tools];
  }

  /**
   * Returns contact information.
   * @returns A friendly message to reach out.
   */
  static contact(): string {
    return 'If you know me, reach me :)';
  }
}
```

<h2 align="center">Skills</h2>

<p align="center">
  <a>
    <img src="https://skillicons.dev/icons?i=typescript,js,nodejs,java,scss,php,python,lua,cs,vue,postgres,mongodb" />
  </a>
</p>
