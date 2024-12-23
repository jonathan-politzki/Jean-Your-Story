# Life Story Generator

## Vision
Life Story Generator is an AI-powered biographical writing system that transforms casual conversations into carefully crafted life stories. Unlike traditional memoir-writing tools that simply collect and compile responses, this system uses advanced AI orchestration to weave individual stories and memories into a coherent, professionally structured biography.

## Key Differentiators
- **Natural Conversation**: Instead of answering rigid prompts, users simply share their stories through voice or text.
- **Intelligent Organization**: AI automatically routes content to relevant biographical sections.
- **Dynamic Writing**: Each section evolves as new content is added, maintaining narrative flow and coherence.
- **Professional Structure**: Content is organized following established biographical frameworks.

## How It Works

### 1. Story Collection
- Users share memories and stories through voice or text
- No need to think about structure or organization
- Natural, conversation-like interaction

### 2. Smart Processing
- AI analyzes each story for themes and timeline
- Content is automatically routed to relevant sections
- Cross-references are maintained between related stories

### 3. Book Generation
- Stories are woven into a coherent narrative
- Professional biographical structure
- Maintains chronological flow where appropriate
- Preserves the authentic voice of the storyteller

## Technical Overview

### Architecture
```
Input Layer (Voice/Text)
       ↓
Content Processing
       ↓
Section Orchestration
       ↓
Narrative Generation
```

### Key Components
- Voice input system
- Content orchestrator
- Section managers
- Narrative generator

## Getting Started

### Prerequisites
```bash
node >= 18.0.0
npm >= 8.0.0
```

### Installation
```bash
# Clone repository
git clone https://github.com/yourusername/life-story-generator.git

# Install dependencies
cd life-story-generator
npm install
```

### Development Setup
```bash
# Start development server
npm run dev

# Run tests
npm test
```

## Project Structure
```
src/
  stores/          # Data management
  services/        # Core business logic
  components/      # UI components
  types/           # TypeScript definitions
```

## Contributing
We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

### Development Guidelines
1. Keep the UI simple and accessible for seniors
2. Maintain clear separation between storage and processing
3. Ensure reliable voice input handling
4. Add comprehensive error handling

## Roadmap

### Phase 1: MVP
- [x] Basic voice/text input
- [x] Simple content routing
- [x] Section generation
- [x] Basic export

### Phase 2: Enhanced Features
- [ ] Advanced narrative generation
- [ ] Cross-referencing system
- [ ] Timeline validation
- [ ] Multiple export formats

### Phase 3: Advanced Features
- [ ] Multi-modal input (photos, documents)
- [ ] Collaborative editing
- [ ] Theme customization
- [ ] Professional printing integration

## Technical Documentation
For detailed technical documentation, see [docs/README.md](docs/README.md)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Inspired by StoryWorth's mission to preserve family stories
- Built on research in biographical writing and narrative structure
- Uses AI technologies from Anthropic's Claude platform

## Contact
For questions or collaboration opportunities, please contact [your-email@example.com]

## About
Life Story Generator is an open-source project dedicated to making life story preservation accessible and meaningful. We believe every life story deserves to be told, and we're using AI to make that process as natural and effective as possible.