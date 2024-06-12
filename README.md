## Getting Started with Create React App

When we first run `create-react-app` there are no folders inside the `src` folder and for most people the first 2 folders they create are a `components` and `hooks` folder. This is a really simple folder structure but for smaller projects with less than 10-15 components to approach.

### `pages`

Each page of the application has its own folder containing a single root file (usually `index.js`) along with any `components`, `hooks`, or other files specific to that page. This localized structure makes it easier to manage and understand page-specific logic.

### `components`

The components folder is further organized into subfolders, such as `ui` and `form` components, to keep the components organized and manageable. This prevents it from becoming overwhelming as the project grows.

### `hooks`

Global `hooks` used across multiple pages are stored here, while page-specific hooks reside in the pages folder. This ensures that hooks are appropriately scoped and organized based on their usage.

### `assets`

All non-code assets like images, CSS files, and fonts are stored here. This keeps the codebase clean and separates design-related assets from the functional code.

### `context`

React context files used across multiple pages are stored here. This centralized location makes it easy to manage and access shared context data throughout the application.

### `data`

Similar to the assets folder, the data folder stores data-related assets like JSON files containing information used in the code. It can also contain files for global constant variables, providing a central location for managing application data.

### `utils`

The utils folder is for storing utility functions, such as formatters, that are used across the application. It's important to keep these functions pure to maintain predictability and ease of testing.
