# eslint-ast-traverser

Extracted traverser class from the ESLint project, this is to allow it to be used by external packages, like ESLint plugins, without the need to rely on the internals of ESLint. This way we avoid breaking changes made when ESLint restrucutres any of it's internals, which can be done even on a patch/minor release and rightfully so since it's not an exposed API in the ESLint package.
