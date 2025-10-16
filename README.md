# 2400031725-skill-exam
rCard.js
import React from 'react';

const UserCard = ({ name, age, bio }) => {
  // Inline styles for the card
  const cardStyle = {
    border: '1px solid #ccc',
    borderRadius: '12px',
    padding: '16px',
    maxWidth: '250px',
    textAlign: 'center',
    boxShadow: '0 4px 8px rgba(0,0,0,0.1)',
    backgroundColor: '#f9f9f9',
    margin: '20px auto',
    fontFamily: 'Arial, sans-serif',
  };

  const nameStyle = {
    fontSize: '1.5rem',
    color: '#333',
    marginBottom: '8px',
  };

  const ageStyle = {
    color: '#555',
    marginBottom: '12px',
  };

  const bioStyle = {
    fontSize: '0.95rem',
    color: '#666',
  };

  return (
    <div style={cardStyle}>
      <h2 style={nameStyle}>{name}</h2>
      <p style={ageStyle}>Age: {age}</p>
      <p style={bioStyle}>{bio}</p>
    </div>
  );
};

export default UserCard;
