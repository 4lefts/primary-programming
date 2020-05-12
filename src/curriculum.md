---
layout: "layout.njk"
title: Curriculum Overview
---

# {{title}}

[The National Curriculum for Computing](https://www.gov.uk/government/publications/national-curriculum-in-england-computing-programmes-of-study) aims to ensure that all pupils:

- can understand and apply the fundamental principles and concepts of computer science, including abstraction, logic, algorithms and data representation
- can analyse problems in computational terms, and have repeated practical experience of writing computer programs in order to solve such problems
- can evaluate and apply information technology, including new or unfamiliar technologies, analytically to solve problems
- are responsible, competent, confident and creative users of information and communication technology.

A complete copy of the National Curriculum Programme of study can be found [here](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/239033/PRIMARY_national_curriculum_-_Computing.pdf). [Primary Programming](/) is only concerned with providing a curriculum and scheme of work for teaching programming, and so, these are the relevant National Curriculum Attaiment Targets...

## Attainment Targets

### KS1

Pupils should be taught to:

- understand what algorithms are; how they are implemented as programs on digital devices; and that programs execute by following precise and unambiguous instructions
- create and debug simple programs
- use logical reasoning to predict the behaviour of simple programs

### KS2

Pupils should be taught to:

- design, write and debug programs that accomplish specific goals, including controlling or simulating physical systems; solve problems by decomposing them into smaller parts.
- use sequence, selection, and repetition in programs; work with variables and various forms of input and output.
- use logical reasoning to explain how some simple algorithms work and to detect and correct errors in algorithms and programs.

## Scheme of Work Objective Overview by Year

We can break down these targets into objectives for each year.

**ALL THIS NEEDS UPDATING**
{%- for curriculum in collections.curricula %}

### {{curriculum.data.title}}

{{curriculum.templateContent}}
{%- endfor -%}
