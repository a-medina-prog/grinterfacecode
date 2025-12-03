demo = gr.Interface(
        fn=CustomChatGPT,
        inputs="text",
        outputs="text",
        title="Real Estate Pro"
)
demo.launch(share=True)
