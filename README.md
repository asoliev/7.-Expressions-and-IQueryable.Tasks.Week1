# 7.-Expressions-and-IQueryable.Tasks
 https://learn.epam.com/learning-piece/sharing?rootId=3850442&itemId=3850449

## Home Task. Expression Transformation

Complete both tasks below. Templates are available in Expressions and IQueryable.Tasks.Week.1.zip

(ExpressionTrees.Task1.ExpressionsTransformer.csproj)

Create a transformer class based on ExpressionVisitor that performs the following 2 types of expression tree transformations:
- Replacing expressions like <variable> + 1 / <variable> - 1 with increment and decrement operations
- Replacing the parameters included in the lambda expression with constants (pass as parameters of such a transformation:
    - Source expression
    - List of pairs <parameter name: value to replace>

For control you can output the resulting tree to the console or watch the result under the debugger.

<b>You can use ExpressionTreeVisualizer or another visualizer here, or you can do it without a visualizer at all.</b>

Complex Task. Mappers. Extended

<b>Extend the logic from the previous task:</b>

Provide the ability to customize the mapping of such fields that differ in names and data types.

Discuss implementation details with mentor.

## Score board:
- 0-59% – Home task is partially implemented.
- 60-79% - Home task is implemented; all tests are green.
- 80-100% - Complex task is implemented. 