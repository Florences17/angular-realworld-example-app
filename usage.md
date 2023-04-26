To use this action in your workflow, add the following step:

name: OpenAI ChatGPT Code Review
uses: adshao/chatgpt-code-review-action@v0.2
with:
    PROGRAMMING_LANGUAGE: 'JavaScript'
    REVIEW_COMMENT_PREFIX: 'chatgpt:'
    FULL_REVIEW_COMMENT: 'chatgpt'
    OPENAI_TOKEN: ${{ secrets.OPENAI_TOKEN }}
    GITHUB_TOKEN: ${{ secrets.GH_TOKEN }}