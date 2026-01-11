# Claude Code Skills Collection

This repository contains custom skills for Claude Code that extend its capabilities in specific domains.

## Available Skills

### 1. Math Problem Solver (`math-solver`)
A comprehensive math problem solver that can handle arithmetic, algebra, calculus, geometry, and statistics problems.

**Description**: Use when Claude needs to solve mathematical problems, perform calculations, or provide step-by-step math solutions.

**Features**:
- Arithmetic operations (addition, subtraction, multiplication, division)
- Algebra (linear equations, quadratic equations, polynomials)
- Calculus (derivatives, integrals, limits)
- Geometry (area, volume, trigonometry)
- Statistics (mean, median, probability)

### 2. Human Organs Reference (`human-organs`)
Comprehensive reference for human organ systems, anatomy, functions, and medical information.

**Description**: Use when Claude needs to provide information about human organs, their functions, anatomical locations, or related medical topics.

**Features**:
- Information on all major organ systems
- Detailed organ descriptions
- Anatomical locations and functions
- Clinical significance information

### 3. Chemistry Periodic Table (`chemistry-periodic-table`)
Comprehensive reference for the periodic table of elements, including atomic properties, groups, periods, trends, and chemical characteristics.

**Description**: Use when Claude needs to provide information about chemical elements, their properties, reactions, or periodic trends.

**Features**:
- Complete periodic table organization
- Element properties and classifications
- Periodic trends information
- Detailed information for key elements
- Group and period classifications

## How to Use These Skills

Each skill is contained in its own directory with the following structure:
```
skill-name/
├── SKILL.md (Main skill file with instructions)
└── references/ (Additional detailed information)
```

To use a skill, Claude Code will automatically recognize when to apply the appropriate skill based on the user's request and the skill's description.

## Installation

These skills are designed to work with Claude Code. Simply place the skill directories in your Claude Code skills folder for them to become available.

## Usage Examples

- For math problems: "Solve 3x + 7 = 25" → Will use math-solver skill
- For biology questions: "What are the functions of the heart?" → Will use human-organs skill
- For chemistry questions: "Tell me about Group 2 elements" → Will use chemistry-periodic-table skill