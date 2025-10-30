# Mini React

A minimal React implementation built from scratch for educational purposes.

## Overview

This project is a step-by-step implementation of React's core features, inspired by Rodrigo Pombo's excellent article ["Build your own React"](https://pomb.us/build-your-own-react/). The goal is to understand how React works under the hood by building a simplified version of it.

## Learning Goals

- Understand React's virtual DOM concept
- Learn about the Fiber architecture
- Implement concurrent rendering
- Build a reconciliation algorithm
- Create function components and hooks
- Gain insights into React's rendering pipeline

## Getting Started
```bash
# Clone the repository
git clone https://github.com/a-shigemichi/mini-react.git
cd mini-react

# Install dependencies (if any)
npm install

# Install serve globally
npm install -g serve

# Start the development server
serve

# View the project in your browser
# Open http://localhost:3000
```

## Implementation Notes

This implementation prioritizes simplicity and educational value over performance and production-readiness. Some features and optimizations present in the real React are intentionally omitted to keep the code focused and understandable.

### Key Differences from Real React

- No optimizations for performance
- Simplified reconciliation algorithm
- No keys for list reconciliation
- No error boundaries
- No context API
- Limited lifecycle methods

## References

- [Build your own React by Rodrigo Pombo](https://pomb.us/build-your-own-react/)
- [React Fiber Architecture](https://github.com/acdlite/react-fiber-architecture)
- [React Codebase Overview](https://reactjs.org/docs/codebase-overview.html)

## Contributing

This is a learning project, but contributions and suggestions are welcome! Feel free to:

- Point out bugs or improvements
- Suggest additional educational features
- Share your own learning experiences

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Note**: This project is for educational purposes only and should not be used in production applications.
