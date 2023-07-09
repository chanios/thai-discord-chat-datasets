# Thai Discord Chat Datasets

This repository contains datasets of Thai Discord chat conversations that were collected between 2016 and 2022. The dataset files are named as data(01-18).txt and collectively contain a total of 28,698,673 lines of chat.

## Dataset Overview

The chat logs are organized in a conversational format, with each line representing a message exchanged between users. The structure of each line follows the convention of Discord chat logs, where user mentions are denoted by "@U" followed by the user's identifier within the chat scope.

### Sample Chat Log:

```
U1:ง้าบเช่นกัน
U2:@U3 นอนยังฮับ
U2:ราตรีสวัสดิ์
*
U1:แล้วโทรศัพท์ก็ดับ
U2:อรุณสวัสดิ์
U2:@U1 @U4 @U3  อรุณสวัสดิ์ฮะ
U1:ทำเช้านี้เค็มจัง เกลือแบบโคตรๆเลยเนี่ย
*
```

## Dataset Collection

The chat data in this repository was collected by me. The collection period spans from 2016 to 2022, ensuring a diverse range of conversations over the years.

## Chat Filtering Rules

The chat data in this repository has been filtered according to the following rules:

1. **Thai Language:** Only chat messages in the Thai language have been included in the dataset.
2. **Exclusion of URLs:** Chat messages containing URLs or links have been omitted from the dataset.
3. **Language Identification:** The [Franc module](https://github.com/wooorm/franc) was utilized to identify the language of each chat message, and only messages identified as "tha" (Thai) were included.
4. **Exclusion of Common Bot Prefix:** Chat messages that start with a common bot prefix have been excluded from the dataset.
5. **Conversational Scope:** Each conversation in the dataset has been restricted to a maximum of 2 hours. If a conversation exceeds this time limit, it is considered a new conversation.
6. **Multiple Real Users:** Each chat conversation in the dataset includes more than two real users engaging in the conversation. Bot users are not counted as part of the user count.

## Usage

Researchers and developers can use this dataset for various purposes, such as natural language processing (NLP) tasks, chatbot training, sentiment analysis, or any other project that requires Thai language chat data. The dataset provides a valuable resource for understanding Thai language usage in Discord conversations over the specified time period.

Please note that the dataset is provided "as is," and I does not guarantee its accuracy or completeness. Users are encouraged to review and preprocess the data according to their specific requirements.

## License

The Thai Discord Chat Datasets repository is made available under the [MIT License](LICENSE). You are free to use, modify, and distribute the dataset in accordance with the terms specified in the license.
