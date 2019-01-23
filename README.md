# dk_prog
## Minimal programming layout for Danes 
### The problem
Special characters `[`, `]`, `{`, `}`, `\`, `~`, and `|` are often used in programming, and yet are notoriously strenuous to type on the Danish keyboard layout. 

Some hackers simply switch to a English keyboard layout altogether to accommodate for this, but this can lead to a lot of frustration because of the unfamiliar placement of `;`, `(`, `<`, etc., which were not relevant for the motivation to switch in the first place.

### The solution
Replace æ, ø, å with these special characters, and make `~` type out instantly instead of functioning as an accent:

| original character | new character | 
| - | - |
 `æ` | `[` 
 `Æ` | `{` 
 `ø` | `]` 
 `Ø` | `}` 
 `å` | `\` 
 `Å` | `|` 
 `~` (accent) | `~` (character) 

The reason that the mentioned keys are so out of the way in the Danish keyboard layout is that they had to yield for æ, ø, å. But since we don't need them for programming, why not add another keyboard layout that does just this, and nothing else?

### Installation
Simply run the relevant MSI installer and restart your computer. On Windows 10, you can swap between layouts using `Win + Space`.

### Contribution
The source is based on the Danish layout and is found in `dk_prog.klc`. Download the [Microsoft Keyboard Layout Editor 1.4](https://www.microsoft.com/en-us/download/details.aspx?id=22339), open the layout source, and navigate Project->Build DLL and Setup Package to build. I edited the source by hand because the GUI did not work properly. 
