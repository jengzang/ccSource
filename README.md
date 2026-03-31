# ccSource

## 简介 | Overview

`ccSource` 是一个基于 TypeScript 的命令行项目源码目录。  
`ccSource` is a TypeScript-based command-line project source repository.

## 目录结构 | Structure

- `src/main.tsx`：主入口，负责启动和初始化流程  
  `src/main.tsx`: Main entry point for startup and initialization.
- `src/commands.ts`：命令注册与命令集合管理  
  `src/commands.ts`: Command registration and command collection management.
- `src/`：核心逻辑、上下文、任务和工具实现  
  `src/`: Core logic, context, task, and tool implementations.
- `extract-sourcemap.mjs`：辅助脚本  
  `extract-sourcemap.mjs`: Helper script.

## 说明 | Notes

- 已添加 `.gitignore`，用于忽略 macOS 生成的 `.DS_Store` 文件，避免误提交。  
  A `.gitignore` file is included to ignore macOS `.DS_Store` files and prevent accidental commits.
