# Common Markdown Features

## **Tables**
Description: A structured way to organize and compare information
Uses:
- Feature comparisons
- Keyboard shortcuts
- Configuration options
- Pricing tiers
- File descriptions
- Command reference

### Best Practice:
- Do not force a procedure into a table. If something has steps, use a numbered list instead

Example from [stevebarakat's Read Me section of the Minimoog](https://github.com/stevebarakat/Minimoog/blob/main/docs/onboarding-readme.md)

## 🔧 Hook API Reference

### `useOnboarding(totalSteps: number = 14)`

#### Parameters

- **`totalSteps`** - Total number of onboarding steps (default: 14)

#### Return Values

| Property                 | Type                          | Description                                 |
| ------------------------ | ----------------------------- | ------------------------------------------- |
| `isVisible`              | `boolean`                     | Whether the onboarding is currently visible |
| `currentStep`            | `number`                      | Current step index (0-based)                |
| `isOnboardingEnabled`    | `boolean`                     | Whether onboarding is enabled in store      |
| `toggleOnboarding`       | `() => void`                  | Toggle onboarding enabled/disabled state    |
| `nextStep`               | `() => void`                  | Move to the next step                       |
| `previousStep`           | `() => void`                  | Move to the previous step                   |
| `closeOnboarding`        | `() => void`                  | Complete and hide onboarding                |
| `resetOnboarding`        | `() => void`                  | Reset to first step and show onboarding     |
| `goToStep`               | `(stepIndex: number) => void` | Jump to a specific step                     |
| `hasCompletedOnboarding` | `boolean`                     | Whether user has completed onboarding       |




## Code Blocks
Description: A way to preserve formatting for code, configuration files, logs, or terminal output
Format: 3 of these `, the codelanguage, then the code

Example from [stevebaraket's Minimoog Audio Processors ReadMe file](https://github.com/stevebarakat/Minimoog/blob/main/docs/audio-processors-readme.md)

### **Load Processors** ##

```typescript
// Load modulation monitor processor
await audioContext.audioWorklet.addModule(
  "/audio/audio-processors/modulation-monitor-processor.js"
);

// Load overload meter processor
await audioContext.audioWorklet.addModule(
  "/audio/audio-processors/overload-meter-processor.js"
);

// Load delay processor
await audioContext.audioWorklet.addModule(
  "/audio/audio-processors/delay-processor.js"
);
```

