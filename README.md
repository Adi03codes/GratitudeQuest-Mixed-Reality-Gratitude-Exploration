# GratitudeQuest-Mixed-Reality-Gratitude-Exploration




**📄 README.md**
```markdown
# GratitudeQuest: Mixed Reality Gratitude Exploration

An MR/AR game that guides users on a real-world gratitude scavenger hunt. Players collect meaningful memories tied to positive emotions.

## Features
- Location-based AR with gratitude prompts
- Integration with journaling and voice input
- Designed for daily mental well-being practices

## Tech Stack
Unity + AR Foundation, C#, Android ARCore, iOS ARKit

## Sample Code Snippets

```csharp
// GratitudeTracker.cs
public class GratitudeTracker : MonoBehaviour {
    public List<string> gratitudeEntries = new List<string>();

    public void AddEntry(string text) {
        gratitudeEntries.Add(text);
        Debug.Log("Entry saved: " + text);
    }
}
