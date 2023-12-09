```typescript
interface Developer {
  summary: string;
  profile: string[];
  interestedIn: string[];
  contact: Contact;
}

interface Contact {
  email: string;
  instagram: string;
}

const sangwonKang: Developer = {
  summary: 'Who love the process of creating a service that will satisfy the user',
  profile: [
    '명지대 정보통신공학과 21학번 (21.03 ~ 22.02)',
    '명지대 정보통신공학과 학회 바코드 (21.03 ~ 22.02)',
    '명지대 자연캠퍼스 중앙동아리 MCC (21.03 ~ 22.02)',
    '명지대 융합소프트웨어학부 데이터테크놀로지전공 (22.03 ~ ing)',
    'DEPth 1기 Frontend Lead (22.02 ~ 23.02)',
    '우아한테크코스 5기 Web Frontend (23.02 ~ 23.10)',
    '(주)나눔비타민 Frontend Lead (23.03 ~ ing)',
  ],
  interestedIn: ['UI/UX', 'DevOps', 'FullStack(App/Web)'],
  contact: {
    email: 'eksovus@gmail.com',
    instagram: 'https://www.instagram.com/ksone__',
  },
};
```
